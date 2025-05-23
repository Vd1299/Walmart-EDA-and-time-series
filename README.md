# Walmart Sales Forecasting

Machine learning project for predicting weekly sales using advanced time series analysis, feature engineering, and XGBoost regression on Walmart historical data.

## 🎯 Overview

End-to-end sales forecasting pipeline with comprehensive EDA, anomaly detection, multiple feature selection techniques, and XGBoost time series modeling for Walmart's 400k+ sales records across 45 stores.

## ⚡ Key Features

- **Exploratory Data Analysis (EDA)**: Statistical insights, correlation analysis, and data visualization
- **Anomaly/Outlier Detection**: Statistical and IQR-based outlier identification and removal
- **Advanced Feature Engineering**: Time-based, lag, rolling window, Trend and seasonality, and interaction features (130+ features)
- **Multiple Feature Selection**: Univariate, Mutual Information, XGboost Feature importance
- **Data Quality Pipeline**: Comprehensive cleaning, validation, and problematic value handling

## 📊 Dataset
Walmart historical sales data (2010-2012):
- **421,570 sales records** across 45 stores and multiple departments
- Store metadata, economic indicators (CPI, unemployment, fuel prices)
- Holiday and seasonal information

## 🔧 Implementation

### Pipeline
1. **EDA & Visualization** → 2. **Anomaly Detection** → 3. **Feature Engineering** → 4. **Feature Selection** → 5. **XGBoost Modeling**

### Feature Selection Methods
- Univariate statistical testing
- Recursive Feature Elimination (RFE)
- Mutual Information scoring
- XGboost importance ranking

### Model
- **XGBoost Regressor**: Optimized for time series forecasting
- Time-aware feature engineering for temporal patterns
- Cross-validation and hyperparameter tuning

## 📈 Results
- **130+ engineered features** from raw data
- **Robust outlier detection** improving data quality
- **Multi-algorithm feature selection** optimizing model performance
- **XGBoost time series model** for accurate sales forecasting

