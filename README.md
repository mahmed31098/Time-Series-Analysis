This report takes you on a comprehensive journey to develop the optimal model for analyzing
time series data. The dataset used consists of the number of aircraft departures in Italy from
1948 to 2014 [Istituto Nazionale di Statistica (ISTAT)].
The process begins with an in-depth analysis of the dataset, assessing its stationarity and
variance. If the series is found to be non-stationary, transformations are applied to achieve
stationarity. Subsequently, model selection is performed using ACF and PACF plots, along
with Information Criteria methods such as AIC, BIC, and HQC.
Once the most suitable models are identified, they are constructed and thoroughly evaluated,
ensuring that the residuals conform to the characteristics of a Gaussian white noise process.
The final stage involves generating forecasts, with the model demonstrating the lowest
RMSE being selected as the best-performing model. This model is then employed to forecast
future values with enhanced accuracy.
All analyses and computations were conducted using Gretl, ensuring robust and reliable
results.
