# Uber-Orbit-Forecast
Time series forecasting using Uber's Orbit and Facebook's Prophet

Objectives: 
----------------------------------------------------------------------------------------------------------------------------------------------------
* Forecast Waze daily mileage data for Italy 
* Forecast average daily temperatures for Italy
* Forecast mileage data using daily temperatures as explanatory variable

Models: 
----------------------------------------------------------------------------------------------------------------------------------------------------
* Orbit Local Global Trend (LGT), Damped Local Trend (DLT) and Exponential Smoothing (ETS)
* Facebook's Prophet
* Arima

Results: 
----------------------------------------------------------------------------------------------------------------------------------------------------
* Prophet yields a smaller prediction error than other forecasting models
* For Orbit models, prediction error increases if temperature is used as a regressor for predicting mileage
* For Prophet, including temperature as a regressor yields a smaller prediction error

References:
----------------------------------------------------------------------------------------------------------------------------------------------------
* https://towardsdatascience.com/time-series-modeling-with-orbit-a38e03a2a4ea
* https://arxiv.org/pdf/2004.08492.pdf

Data sources: 
----------------------------------------------------------------------------------------------------------------------------------------------------
* Waze mileage data: https://github.com/ActiveConclusion/COVID19_mobility
* Temperature data: https://github.com/GoogleCloudPlatform/covid-19-open-data
