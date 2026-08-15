# Dataset

## Overview

This folder contains the weekly Lassa fever surveillance dataset used for the machine learning forecasting and outbreak classification analysis.

The dataset contains epidemiological records covering the period from 2020 to 2025 and supports temporal modelling of confirmed cases, suspected cases, deaths, and outbreak activity.

## Main Variables

The core variables used in the analysis include:

- `week_start_date` – beginning date of the epidemiological week
- `week_end_date` – ending date of the epidemiological week
- `epi_year` – epidemiological year
- `epi_week` – epidemiological week number
- `suspected_cases` – number of suspected Lassa fever cases
- `confirmed_cases` – number of confirmed cases
- `deaths` – number of reported deaths

Additional temporal and engineered variables are created inside the Jupyter Notebook during preprocessing and feature engineering.

## Modelling Targets

Two prediction tasks are implemented:

1. **Regression:** forecasting weekly confirmed Lassa fever cases
2. **Classification:** predicting outbreak status

## Data Preparation

The analysis includes:

- missing-value assessment
- date conversion and validation
- temporal ordering
- lag feature generation
- rolling statistics
- seasonal and calendar features
- leakage validation
- chronological train-validation-test partitioning

## Temporal Split

The modelling framework uses a chronological split to preserve temporal integrity:

- Training: historical observations up to 2023
- Validation: 2024
- Independent Test: 2025

## Data File

`lassa_fever.csv`
