# Predicting Walmart Stock Price

A time-series forecasting example. It takes historical Walmart stock closing prices and produces a 10-day forecast using several simple, interpretable methods.

## Methods compared

- 30-day moving average
- 5-day weighted moving average
- Exponential smoothing (Holt's method, smoothing levels 0.3 and 0.8)
- Linear regression trend

## Tech stack

- Python
- pandas / NumPy
- statsmodels (Holt / exponential smoothing)
- scikit-learn (linear regression)
- Matplotlib

## Data

`WalMartStock.csv` — historical daily closing prices, indexed by date.

## What's in the notebook

1. Load and prep the stock data as a time series
2. Generate 10-day-ahead forecasts with each method
3. Plot all forecasts together for visual comparison
