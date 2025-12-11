# Customer Churn Prediction

## Overview
A machine learning project to predict customer churn using telco data.  
This repository contains a Jupyter notebook that demonstrates data loading, preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and visualization for churn prediction.

## Repository structure
- `project1.ipynb` — main Jupyter notebook with full pipeline (EDA → preprocessing → modeling → evaluation).  
- `Telco_customer_churn.xlsx` — dataset used for modelling (place under `data/` if you prefer).  
- `README.md` — this file.

## Key steps implemented
1. Load dataset and inspect data quality (missing values, datatypes).  
2. Data cleaning and preprocessing: encoding categorical features, handling missing values, and any necessary scaling.  
3. Exploratory Data Analysis (feature distributions, correlations, target imbalance checks).  
4. Split data into train and test sets.  
5. Train and evaluate classification models.  
6. Evaluate using metrics and visualizations: classification report, ROC AUC, confusion matrix, feature importances.  
7. (Optional) Hyperparameter tuning and cross-validation for model selection.

## Models experimented with
- Logistic Regression  
- Random Forest  
- XGBoost

## Metrics reported
- Classification report (precision / recall / f1-score)  
- ROC AUC  
- Confusion matrix

## Requirements / Setup
It is recommended to use a virtual environment.
