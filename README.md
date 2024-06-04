# financial-models
# Time Series Forecasting Model (ARIMA)

This project demonstrates a time series forecasting model using the ARIMA (AutoRegressive Integrated Moving Average) method. The model is applied to stock price data to forecast future prices.

## Requirements

- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib

## Setup

1. Clone the repository:

2. Install the required packages:

3. Run the `time_series_forecasting.py` script to see the model in action:

## Explanation

- **Load Data**: Load the time series data from a CSV file or generate random data for demonstration.
- **Stationarity Check**: Perform the Augmented Dickey-Fuller test to check if the series is stationary.
- **Differencing**: Difference the data to achieve stationarity if necessary.
- **ARIMA Model**: Fit the ARIMA model and print the summary.
- **Forecasting**: Forecast future values and plot the results.

## Results

The forecasted values and confidence intervals are plotted along with the historical data.
