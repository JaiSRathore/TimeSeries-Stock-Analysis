# Stock Price Time Series Forecasting

## Overview

This project performs time series analysis and forecasting on adjusted closing stock prices using various models (ARIMA, ETS, LSTM, Prophet). It includes Exploratory Data Analysis (EDA), time series decomposition, model training, evaluation, and an interactive Streamlit web application for visualization and user interaction.

**Project Doc:** [https://lapis-school-f5e.notion.site/Stock-Price-Time-Series-Forecasting-1e4ca101e46980ecadd0c80f0c1fff64?pvs=4]

## Features

*   Analyzes and forecasts prices for MARA, SOXL, TD_BANK, NVDA, MANULIFE (or user-uploaded data).
*   Compares ARIMA (auto-tuned), ETS (grid-tuned), LSTM (stabilized), and Prophet models.
*   Visualizes raw data, decomposition components, and forecast results.
*   Provides standard accuracy metrics (RMSE, MAE, MAPE, MSE).
*   Interactive Streamlit application for user exploration.

## Tech Stack

*   Python
*   Pandas, NumPy
*   Statsmodels, pmdarima, Prophet, Scikit-learn, TensorFlow/Keras
*   Matplotlib, Seaborn
*   Streamlit
