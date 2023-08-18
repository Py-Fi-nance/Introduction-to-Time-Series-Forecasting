# Introduction-to-Time-Series-Forecasting
In depth introduction to time series forecasting covering a broad range of models.
This notebook provides an example of time series analysis on NASDAQ daily closing prices. It includes data loading, visualization, handling missing values, decomposition, hyperparameter tuning for different moving averages, ARIMA modeling, and various statistical diagnostic tests.

![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![Forks](https://img.shields.io/github/forks/Py-Fi-nance/Introduction-to-Time-Series-Forecasting)](https://github.com/Py-Fi-nance/Introduction-to-Time-Series-Forecasting/network)
[![Stars](https://img.shields.io/github/stars/Py-Fi-nance/Introduction-to-Time-Series-Forecasting)](https://github.com/Py-Fi-nance/Introduction-to-Time-Series-Forecasting/stargazers)


## Table of Contents
1. [Installation](#installation)
2. [Data Loading](#data-loading)
3. [Data Visualization](#data-visualization)
4. [Handling Missing Values](#handling-missing-values)
5. [Time Series Decomposition](#time-series-decomposition)
6. [Moving Averages](#moving-averages)
7. [Autocorrelation and Partial Autocorrelation](#autocorrelation-and-partial-autocorrelation)
8. [Stationarity Tests](#stationarity-tests)
9. [ARIMA Modeling](#arima-modeling)
10. [Model Diagnostics](#model-diagnostics)
11. [Contributing](#contributing)
12. [Contact Information](#contact-information)


## Installation <a name="installation"></a>
```bash
!pip install openbb pandas numpy matplotlib statsmodels scikit-learn
```
##  Data Loading <a name="data-loading"></a>
```bash
from openbb_terminal.sdk import openbb
df_daily = openbb.stocks.load(symbol = 'ndaq')
```
## Data Visualization <a name="data-visualization"></a>
Plots for NASDAQ daily closing prices, trend, seasonal, and residual components.

##  Handling Missing Values <a name="handling-missing-values"></a>
Code to identify and handle missing values in the dataset.

##  Time Series Decomposition <a name="time-series-decomposition"></a>
Decomposing the time series into observed, trend, seasonal, and residual components.

##  Moving Averages <a name="moving-averages"></a>
Implementation and evaluation of Simple Moving Average (SMA) and Exponential Weighted Moving Average (EWMA) with hyperparameter tuning.

##  Autocorrelation and Partial Autocorrelation <a name="autocorrelation-and-partial-autocorrelation"></a>
Visualizing and interpreting the autocorrelation and partial autocorrelation functions.

##  Stationarity Tests <a name="stationarity-tests"></a>
Includes Dickey-Fuller tests and differencing to achieve stationarity.

##  ARIMA Modeling <a name="arima-modeling"></a>
ARIMA modeling includes the process of identifying the best-fitting ARIMA model for the time series and making predictions.

##  Model Diagnostics <a name="model-diagnostics"></a>
Residual analysis including ACF and PACF of residuals and squared residuals, Ljung-Box test, Kolmogorov-Smirnov test. Includes Goldfeld-Quandt test to identify any heteroskedasticity in the residuals.

## Contributing <a name="contributing"></a>
We welcome contributions to this project. To contribute:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.


## Contact Information <a name="contact-information"></a>
For any questions or inquiries, please contact support@pyfi.com - Subject: Github Repo Q, Sentiment-Analysis-for-Nvidia-Stock.
For a full article walkthrough please visit > https://www.pyfi.com/blog/Introduction-to-Time-Series-Forecasting < where you'll also be able to pick up a complimentary copy of the complete, Volume I text of our Machine Learning Edge Blueprint, a $49 value. This text will walk you through everything you need to get started coding Python for Finance
[![Follow on LinkedIn](https://img.shields.io/badge/Follow%20on-LinkedIn-blue?style=social&logo=linkedin)](https://www.linkedin.com/company/pyfi/)
