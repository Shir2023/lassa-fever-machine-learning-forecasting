# Project Visualizations

## Overview

This folder contains the key visual outputs generated from the Lassa fever machine learning forecasting and outbreak classification analysis.

The figures summarize temporal patterns, model performance, forecasting accuracy, and classification effectiveness.

## Visualizations

### Weekly Confirmed Cases

`weekly_confirmed_cases.png`

Shows the temporal pattern of weekly confirmed Lassa fever cases across the study period. The figure highlights recurring seasonal peaks and changes in disease activity over time.

### Regression Model Comparison

`regression_model_comparison.png`

Compares the final regression models using MAE, RMSE, MAPE, and R². The visualization supports comparison of forecasting performance across Support Vector Regression, Linear Regression, XGBoost, and Random Forest.

### Actual vs Predicted Cases

`actual_vs_predicted_2025.png`

Compares the observed weekly confirmed cases with predictions from the best-performing regression model on the independent 2025 test dataset.

### Classification Model Comparison

`classification_model_comparison.png`

Compares the classification models using Accuracy, Precision, Recall, F1-score, and ROC-AUC.

### Confusion Matrix

`confusion_matrix.png`

Shows the classification performance of the selected outbreak prediction model by comparing predicted and observed outbreak classes.

### ROC Curve

`roc_curve.png`

Displays the ROC curves of the optimized classification models on the independent 2025 test dataset and illustrates their ability to distinguish outbreak from non-outbreak observations.
