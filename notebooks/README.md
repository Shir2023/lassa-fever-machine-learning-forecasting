# Lassa Fever Machine Learning Forecasting and Outbreak Classification

## Project Overview

This project develops a leakage-aware temporal machine learning framework for forecasting weekly confirmed Lassa fever cases and classifying outbreak activity using surveillance data.

The analysis combines exploratory data analysis, temporal feature engineering, regression modelling, classification modelling, hyperparameter optimization, and independent-year evaluation.

To preserve temporal integrity, historical observations are used for model development, 2024 is used for validation, and 2025 is retained as an independent test period.

## Project Objectives

1. Analyse temporal patterns in weekly Lassa fever surveillance data.
2. Engineer lag-based, rolling, and calendar-related predictive features.
3. Develop and compare regression models for weekly case forecasting.
4. Develop classification models for outbreak-status prediction.
5. Optimize model hyperparameters and evaluate performance on an independent temporal test dataset.

## Machine Learning Workflow

Data Loading → Data Quality Assessment → Exploratory Data Analysis → Temporal Feature Engineering → Leakage Validation → Chronological Data Split → Baseline Modelling → Hyperparameter Optimization → Independent-Year Testing → Model Evaluation

## Import the libraries
