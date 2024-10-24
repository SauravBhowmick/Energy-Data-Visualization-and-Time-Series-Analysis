# Energy Data Engineering-2-Project1
ARIMA models

## Energy Data Visualization and Time Series Analysis
Problem Statement: How CO2 is effected by energy sources. A detailed data visualisation needs to be done to identify the trends. Create a synthetic model for the future year by fitting to the best ARIMA model.

### Features:
#### Data Visualization:
- Visualize the energy data to identify patterns and trends effectively.

![Alt text](https://github.com/SauravBhowmick/Energy-Data-Visualization-and-Time-Series-Analysis/blob/main/EDE2_Project1_visual.JPG)

We can see from the graph that the energy source is more occuring in 2000-4000MW.

#### Trend and Seasonal Decomposition:
- Perform additive decomposition since seasonal growth is almost varying around 6000.
![Alt text](https://github.com/SauravBhowmick/Energy-Data-Visualization-and-Time-Series-Analysis/blob/main/EDE2_Project1_visual2.JPG)

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
- Created a synthetic profile for 2024.
- Deployed a statistical model for the residuals to closely imitate the time series in terms of autocorrelation, moving average, variance, and mean.
