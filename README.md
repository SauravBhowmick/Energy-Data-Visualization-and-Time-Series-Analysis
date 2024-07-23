# EDE2_Project1
ARIMA models

## Energy Data Visualization and Time Series Analysis
This repository contains scripts and models for visualizing energy data and performing comprehensive time series analysis. The focus is on trend and seasonal decomposition, daily profile decomposition, and ARIMA model selection and deployment.

### Features:
#### Data Visualization:
- Visualize the energy data to identify patterns and trends effectively.

#### Trend and Seasonal Decomposition:
- Perform additive decomposition since seasonal growth is almost varying around 6000.

#### Decomposition of Daily Profiles:
- Break down daily energy profiles to understand underlying patterns.

#### Model Selection:
- Residuals Stationarity: Check stationarity of residuals using the Augmented Dickey-Fuller (adfuller) test.
- Autocorrelation Analysis: Plot the autocorrelation and partial autocorrelation functions for residuals.
- ARIMA Model Comparison: Compare at least 5 different ARIMA models based on parameters p, d, and q.
- Evaluate models using the Ljung-Box test to check the quality of fit.

#### Model Deployment:

##### Rolling Forecast:
- Deploy a rolling forecast on the last year of training data.
- Visualize the forecast including uncertainty ranges.
- Evaluate forecast quality using RMSE (Root Mean Square Error).
##### Synthetic Profile Creation:
- Create a synthetic profile for 2024.
- Deploy a statistical model for the residuals to closely imitate the time series in terms of autocorrelation, moving average, variance, and mean.
