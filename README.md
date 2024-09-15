# Customer Churn Analysis and Prediction

This repository contains a machine learning pipeline for predicting customer churn using an E-commerce dataset. The project involves data cleaning, exploratory data analysis (EDA), feature engineering, and model building using several classification algorithms.

## Project Overview

- **Data Preprocessing**: 
  - Handles missing values, outliers, and encodes categorical variables (label encoding, one-hot encoding).
  - Standardizes numerical features for improved model performance.

- **Exploratory Data Analysis (EDA)**:
  - Analyzes numerical and categorical variables, visualizes relationships with the target variable (`Churn`) using count plots, box plots, heatmaps, and correlation matrices.

- **Modeling**:
  - Implements several machine learning models including:
    - Logistic Regression
    - K-Nearest Neighbors (KNN)
    - Support Vector Classifier (SVC)
    - Decision Trees
    - RandomForest
    - XGBoost, LightGBM, CatBoost
  - Applies cross-validation to evaluate models using `ROC_AUC`, `Accuracy`, and `F1 Score`.

- **Hyperparameter Tuning**:
  - Uses `GridSearchCV` to optimize hyperparameters for key models like RandomForest, XGBoost, and LightGBM.

- **Ensemble Learning**:
  - Combines top-performing models (KNN, RandomForest, LightGBM) using a soft **Voting Classifier** for enhanced performance.

- **Feature Importance**:
  - Visualizes feature importance for the best models to identify key drivers of customer churn.

## Project Structure

- `E Commerce Dataset.xlsx`: Input dataset containing customer data for churn analysis.
- `main.py`: Main Python script containing data preprocessing, EDA, model building, and evaluation.
- `README.md`: Project overview and instructions.

