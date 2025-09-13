# CO2 Forecasting with Time Series 
## Overview
This analysis focuses on CO2 atmospheric concentrations dataset. It contains data preparation and exploration using visualization and STL decomposition, and building a seasonal ARIMA model used for producing one-step ahead, dynamic, and future forecasts.

## Resources Used
- Python 3.7
- Numpy and Pandas for data manipulation
- Matplotlib and pylab for visualization
- statsmodels library for building the seasonal ARIMA model

## Dataset
The CO2 dataset contains 2284 observations which are atmospheric CO2 collected samples from March 1958 to December 2001:
- **date**: sample date in YYMMDD format
- **co2**: CO2 Concentration ppmv

## Data Preparation and Exploration
-	Resample data using monthly averages
-	Handle missing values 
-	Visualize and decompose the time series in trend, seasonality, and noise 
-	Check stationarity using the Dickey-Fuller test
-	Compute and plot the ACF and PACF values

## Build the ARIMA model
-	Applied grid search to identify the best parameters for fitting the model 
-	Built the model and used it for producing one-step ahead, dynamic, and future forecasts

The visualizations confirmed that the overall forecasts were accurate for both one-step ahead and dynamic forecasts. The future forecasts indicate that the CO2 time series is expected to continue increasing.
