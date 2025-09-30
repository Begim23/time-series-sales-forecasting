# Sales Forecasting with Machine Learning

## Overview
This project predicts sales using time series data combined with categorical and numerical features.  
We applied **Random Forest, XGBoost, AdaBoost, and LSTM** to compare performance.

## Features
- Exploratory Data Analysis (EDA) with visualizations
- Feature engineering (lags, rolling, seasonal trends, cumulative sales, etc.)
- Outlier detection & handling
- Model training, hyperparameter tuning, and comparison
- Sales insights for better business decisions

## Models & Results
| Model         | RMSE   | MAE   |
|---------------|--------|-------|
| Random Forest | 0.13   | 0.05  |
| XGBoost       | 1.01   | 0.56  |
| AdaBoost      | 7.84   | 6.35  |
| LSTM          | 110.85 | 84.50 |

 **Best Model: Random Forest**

## Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn, Statsmodels
- Scikit-learn, XGBoost, TensorFlow/Keras

## How to Run
```bash
git clone https://github.com/username/sales-forecasting-ml.git
cd sales-forecasting-ml
pip install -r requirements.txt
python src/train_model.py
