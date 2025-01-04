Net Interest Income (NII) Forecasting for HDFC Bank and SBI

Overview

This repository contains the project for forecasting the Net Interest Income (NII) for HDFC Bank and SBI on a quarterly basis using Univariate and Multivariate Time Series Analysis techniques. The analysis also includes identifying causal relationships between NII and key economic and financial metrics.

Key Features

1. Forecasting Models

Univariate Time Series Models:

ARIMA (AutoRegressive Integrated Moving Average)

Exponential Smoothing

Forecast Accuracy:

HDFC Bank: 92%

SBI: 89%

2. Causality Analysis

Granger Causality Test:

Examined the causal relationship of NII with key metrics such as:

Gross Advances

GNPA Ratio

CASA Ratio

PCR

Lending and Deposit Interest Rates

GDP

Significant relationships were identified in 5 out of 7 factors (p-value < 0.05).

3. Data Stationarity and Modeling

Ensured stationarity of the time series using the ADF (Augmented Dickey-Fuller) Test.

Non-stationary series were transformed to stationary through differencing.

Built and evaluated:

Vector AR (AutoRegressive) Model

Vector ARIMA (AutoRegressive Integrated Moving Average) Model

4. Model Performance

Mean Absolute Percentage Error (MAPE):

Vector AR: 10.1%

Vector ARIMA: 9.4%

Tools and Techniques Used

Statistical Tests:

ADF Test for stationarity

Granger Causality Test

Time Series Models:

ARIMA

Exponential Smoothing

Vector AR

Vector ARIMA

Metrics for Model Evaluation:

MAPE

Forecast Accuracy

Results

The forecasting models demonstrated strong predictive power:

ARIMA and Exponential Smoothing models provided quarterly NII forecasts with high accuracy.

Multivariate models (Vector AR and Vector ARIMA) highlighted significant interactions between NII and macroeconomic factors, with MAPE values of 10.1% and 9.4%, respectively.

Conclusion

This analysis provides a robust methodology for forecasting NII and understanding its dependency on financial and economic metrics. The results can guide strategic decision-making for banks by identifying key drivers of NII and providing accurate forecasts for financial planning.
