# Fraud Detection for E-commerce and Bank Transactions

## Project Overview
This project focuses on improving fraud detection in e-commerce and bank credit transactions using advanced machine learning techniques. The aim is to build robust models that balance fraud detection accuracy with minimizing false positives, thus enhancing transaction security and customer trust.

## Datasets
- `Fraud_Data.csv`: E-commerce transaction data with user, device, and transaction details.
- `IpAddress_to_Country.csv`: IP address ranges mapped to countries for geolocation analysis.
- `creditcard.csv`: Bank transaction data with anonymized features for fraud detection.

## Features & Engineering
- Time-based features (hour of day, day of week, time since signup)
- Transaction frequency and velocity metrics
- IP address geolocation mapping
- Handling imbalanced classes using SMOTE and undersampling
- Encoding categorical variables and normalization

## Modeling
- Logistic Regression as baseline
- Ensemble models: Random Forest / Gradient Boosting (XGBoost / LightGBM)
- Model evaluation with metrics suitable for imbalanced data: AUC-PR, F1-Score, Confusion Matrix
- Best model selection justified based on business and technical performance

## Model Explainability
- SHAP (Shapley Additive Explanations) used to interpret model predictions
- Visualizations of global and local feature importance
- Insights into key factors driving fraud detection

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Alki45/fruad-detection-e-commerce.git
   cd fraud-detection
