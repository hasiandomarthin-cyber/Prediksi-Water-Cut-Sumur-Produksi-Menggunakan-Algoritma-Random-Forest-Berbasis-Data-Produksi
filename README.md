# Water Cut Prediction using Random Forest

This repository contains the source code developed for my undergraduate thesis:

**"Prediction of Water Cut in Production Wells Using Random Forest Based on Production Data."**

## Overview

This project develops a machine learning model to predict water cut in mature oil fields using historical daily production data. The workflow includes:

- Data cleaning and preprocessing
- Savitzky-Golay smoothing
- Temporal feature engineering (28 engineered features)
- Time-series train-test split
- Random Forest Regression
- Hyperparameter tuning
- Model evaluation (R², MAE, RMSE)
- Feature importance analysis
- Cold-start evaluation
- Prediction interval analysis

## Dataset

- 79 production wells
- 164,527 production records
- Four artificial lift systems:
  - ESP
  - SRP
  - PCP
  - HPU

> **Note:** The production dataset is confidential and is not included in this repository.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- OpenPyXL
- Jupyter Notebook
- 
