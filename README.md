Contents: 

GARCH Example.ipynb
Simulates and models time series volatility using a GARCH(2,2) model. 
Uses synthetic data to replicate realistic financial volatility. 
Implements arch_model from the arch package. 
Includes ACF/PACF plots and a summary of model results.

SARIMA forecast example.ipynb
Performs forecasting on business revenue data using a SARIMA (Seasonal ARIMA) model. 
Reads a sample dataset with daily revenue values. 
Splits the data into training/testing sets. 
Fits a SARIMA model and plots forecast vs. actuals. 
Evaluates accuracy with MAE, RMSE, and MAPE.

fake_sales_data.xlsx
A sample dataset with daily revenue for fictional store locations. 
Designed to have upward trends and realistic noise. 
Used as input for SARIMA modeling in the notebook.

Requirements:

numpy pandas matplotlib statsmodels arch openpyxl

Disclaimer:

This repository uses entirely synthetic and anonymized data. 
It is intended for educational and portfolio purposes only and does not reflect any real company data.
