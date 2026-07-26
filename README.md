# Cryptocurrency Volatility Prediction Using Machine Learning Models

**HAR-X, XGBoost, and LightGBM applied to Bitcoin realized volatility forecasting**

Research paper for the *Machine Learning for Finance* course (MSc Economics, University of Bonn).

## Overview

This project forecasts the one-day-ahead **realized volatility (RV)** of Bitcoin using linear and machine learning models, and compares how much internal (crypto-specific) versus external (macro/market) predictors contribute to forecasting performance.

Six models are estimated and compared across three sample splits:

- **HAR-X**, estimated via four methods: OLS, Ridge, Lasso, and Gamma regression
- **XGBoost**
- **LightGBM**

Models are evaluated with RMSE, MAE, and QLIKE (and their naive-benchmark-scaled versions: RMSSE, MASE, QLIKES), and compared via a post-forecast feature importance analysis.

## Repository contents

| File | Description |
|---|---|
| `btc_dataset_new.csv` | Final processed dataset used for modeling |
| `code_gridneva.ipynb` | Data preprocessing, model estimation, hyperparameter tuning, evaluation, feature importance analysis |
| `paper_gridneva.pdf` | Full research paper |


## How to reproduce

Run `code_gridneva.ipynb` using the provided `btc_dataset_new.csv`

## Author

Karina Gridneva
