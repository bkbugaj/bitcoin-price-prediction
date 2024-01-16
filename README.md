# Bitcoin Price Prediction

## Overview
The repository contains a Jupyter notebook (`bitcoin-price-prediction.ipynb`) for Bitcoin price prediction using `Long Short-Term Memory (LSTM)` neural networks. The project includes model training, hyperparameter tuning, and the results of different model experiments.

## Files and Directories

#### bitcoin-price-prediction.ipynb
- This jupyter notebook covers the data preparation, development of the model and the hyperparameter tuning using `RandomizedSearchCV`.

#### data/ohlcv_data.pkl
- This file contains the `Bitcoin to Euro` time series dataset used for training the model and conducting hyperparameter tuning.

#### experiments/experiments.txt
- This file stores the outcomes of multiple runs of `RandomizedSearchCV`. Each entry includes the `Mean Absolute Error (MAE)`, `Mean Absolute Percentage Error (MAPE)`, and `R-squared (R2)` values calculated for the best estimator identified by `RandomizedSearchCV`.
- The hyperparameter values of the best estimator are documented for reference.

#### models
- This directory contains the saved models.
- Two key models are included: the `baseline model` and the `best model` obtained after hyperparameter tuning.