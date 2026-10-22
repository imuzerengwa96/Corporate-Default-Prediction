# Corporate-Default-Prediction
Using machine learning models for Corporate Default Prediction

## Overview
Predicting corporate default using financial statements, market data, and macroeconomic indicators with Machine Learning. The analysis used the rolling window method for the one-year-ahead corporate default prediction.

## Models
The models that were used are:
- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- Catboost
- Artificial Neural Network

## Class Balancing Strategies
Due to severe class imbalance, the analysis also compared the models performance using different class balancing strategies which were:
- Native (None)
- Class weighting
- SMOTE
- SMOTETOMEK
- Random undersampling
- Random oversampling

## Skills Demonstrated
- Data collection, cleaning, and feature engineering
- Supervised Machine Learning (Logistic Regression, Random Forest, XGBoost, ANN)
- Model evaluation (ROC-AUC, F1-score)
- Deployment (Streamlit/Flask)

## Repository Structure
- `data/` - raw and processed datasets
- `notebooks/` - Jupyter notebooks for analysis
- `scripts/` - Python/R scripts for preprocessing and modeling
- `models/` - saved trained models
- `app/` - deployed ML application

## Usage
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run notebooks or scripts as needed
