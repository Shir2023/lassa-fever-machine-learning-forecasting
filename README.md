# Lassa Fever Machine Learning Forecasting

A leakage-aware machine learning framework for forecasting weekly Lassa fever cases and classifying outbreak status using temporal surveillance data.

## Project Overview

This project applies machine learning to weekly Lassa fever surveillance data to forecast confirmed cases and classify outbreak activity.

The workflow includes data preprocessing, exploratory analysis, temporal feature engineering, leakage prevention, regression modelling, classification modelling, hyperparameter optimization, and independent-year evaluation.

## Machine Learning Workflow

Data Collection → Data Cleaning → Exploratory Data Analysis → Temporal Feature Engineering → Leakage Validation → Chronological Data Split → Model Training → Hyperparameter Optimization → Independent Test Evaluation

## Models Used

### Regression Models
- Linear Regression
- Random Forest Regressor
- Support Vector Regressor
- XGBoost Regressor

### Classification Models
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine
- XGBoost Classifier

## Validation Strategy

The dataset was divided chronologically to preserve temporal integrity:

- Training: Historical observations up to 2023
- Validation: 2024
- Independent Test: 2025

This approach reduces temporal information leakage and provides a more realistic evaluation of model performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Optuna
- Matplotlib
- Jupyter Notebook

## Project Files

The repository will contain:

- Jupyter Notebook containing the complete machine learning workflow
- Model evaluation results
- Visualizations
- Supporting documentation

## Author

**Paul Shir**

Data Analytics | Data Science | Machine Learning
