# Sweden Electricity Price Forecasting

This project analyzes and forecasts Sweden's electricity prices using time series methods, including trend analysis, stationarity checks, ARIMA modeling, and forecasting.

## Data
- **Source:** `european_wholesale_electricity_price_data_daily.csv`
- **Timeframe:** February 1 - March 3, 2024
- **Columns Used:** `Date`, `Price (EUR/MWhe)`, `Country`

## Features
- Time series decomposition (trend, seasonality, residuals)
- Stationarity test (ADF test)
- ARIMA model selection (optimized using AIC and PACF/ACF)
- 10-day price forecasting

