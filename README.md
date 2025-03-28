# SARIMAX Forecasting for Vimana Time Series Data with MAPE Evaluation

This repository provides a Python implementation of the SARIMAX model for forecasting Vimana time series data, along with MAPE for model evaluation.

## Purpose:

* Demonstrates time series forecasting for Vimana data using the SARIMAX model, which accounts for seasonality and external factors.
* Implements MAPE (Mean Absolute Percentage Error) for accurate model performance evaluation.
* Provides a foundation for understanding advanced time series analysis in the context of Vimana-related data.

## Implementation:

* Uses Python's `statsmodels` library to implement the SARIMAX model.
* Allows for parameter tuning (p, d, q, P, D, Q, s) based on Vimana data analysis.
* Implements the MAPE metric for evaluating forecast accuracy.
* Provides functionality for visualizing historical Vimana data, forecasts, and model performance.

## Usage:

1.  Install necessary Python packages (e.g., `pandas`, `numpy`, `matplotlib`, `statsmodels`, `sklearn`).
2.  Input your Vimana time series data (with potential exogenous variables).
3.  Run the provided Python script (`vimana_sarimax_mape_forecast.py`).
4.  Specify the desired SARIMAX parameters (p, d, q, P, D, Q, s).
5.  Interpret output:
    * The script outputs forecasted Vimana data values.
    * Visualizations of historical and forecasted data are generated.
    * The MAPE score is calculated and displayed.
    * Other model performance metrics are included.

## Key Concepts:

* **SARIMAX (Seasonal Autoregressive Integrated Moving Average with eXogenous regressors):** A time series forecasting model that extends ARIMA to handle seasonality and external variables.
* **p, d, q:** ARIMA parameters (autoregressive, differencing, moving average orders).
* **P, D, Q, s:** Seasonal ARIMA parameters (seasonal orders and seasonality period).
* **MAPE (Mean Absolute Percentage Error):** A metric for evaluating forecast accuracy, expressed as a percentage.
* **Exogenous Variables:** External factors that can influence the Vimana time series.
* **Time Series Analysis:** Analyzing data points collected over time, specifically related to Vimana.
* **Forecasting:** Predicting future Vimana data values based on historical data.

## Output:

* Forecasted Vimana time series values.
* Visualizations of historical and forecasted Vimana data.
* MAPE score.
* Information about the parameters used (p, d, q, P, D, Q, s).
* Other model performance evaluation metrics.
