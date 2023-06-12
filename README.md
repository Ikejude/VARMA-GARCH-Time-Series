# VARMA Time Series Analysis of Nigeria Stock Exchange
This repository contains a VARMA (Vector Autoregressive Moving Average) time series analysis of the Nigeria Stock Exchange. The analysis aims to model and forecast the behavior of stock prices and trading volumes in the Nigerian market.

## Dataset
The analysis utilizes a dataset of historical stock prices and trading volumes from the Nigeria Stock Exchange. The dataset includes daily or interval-based data for multiple stocks traded on the exchange. It serves as the input for the VARMA model to capture the interdependencies and dynamics among the stock variables.

## Model Description
The VARMA model is a multivariate time series analysis technique that combines vector autoregression (VAR) and moving average (MA) components. It allows for the examination of the relationships and dependencies between multiple time series variables, making it suitable for analyzing stock market data.

**`Key steps of the analysis include`**:

* Data Preprocessing: Cleaning and transforming the input data to ensure consistency and stationarity. This may involve handling missing values, outlier detection and treatment, and performing necessary transformations like differencing or logarithmic transformations.

* Model Identification: Determining the appropriate lag order for the VARMA model by analyzing autocorrelation and partial autocorrelation functions (ACF/PACF) and considering statistical tests such as the Akaike Information Criterion (AIC) or Bayesian Information Criterion (BIC).

* Model Estimation: Fitting the VARMA model to the preprocessed dataset. This involves estimating the model parameters using techniques such as maximum likelihood estimation or least squares.

* Model Diagnostics: Evaluating the goodness of fit and diagnosing the VARMA model. This includes assessing the residuals for stationarity, independence, and normality assumptions, as well as conducting diagnostic tests like the Ljung-Box test or the Portmanteau test.

* Forecasting: Using the estimated VARMA model to generate future forecasts of stock prices and trading volumes in the Nigeria Stock Exchange.

## Usage
To use the VARMA time series analysis on the Nigeria Stock Exchange dataset, follow these steps:

* Preprocess the input dataset according to the provided guidelines in the data_preprocessing.py script. This ensures the data is in the appropriate format and meets the stationarity requirements for VARMA modeling.

* Identify the appropriate lag order for the VARMA model by analyzing the ACF/PACF plots and conducting statistical tests. Modify the lag order in the model_identification.py script to suit your dataset.

* Run the varma_garch_analysis.ipynb script, providing the preprocessed dataset and selected lag order as input. The script will estimate the VARMA model and provide diagnostic information.

* Use the estimated VARMA model to generate future forecasts. Adjust the forecast horizon and other parameters as needed.

## Evaluation
Evaluation of the VARMA model can be performed by assessing the goodness of fit, checking for stationarity and normality of residuals, and validating the accuracy of the forecasts. Various metrics such as mean squared error (MSE) or mean absolute percentage error (MAPE) can be used to measure the forecast accuracy.

## Contributions
Contributions to this project are welcome. If you find any issues, have suggestions for improvements, or want to contribute new features, please feel free to submit a pull request.

## License
This project is not licensed.
