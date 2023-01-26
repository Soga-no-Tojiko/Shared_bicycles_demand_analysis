# Shared_bicycles_demand_analysis

This project employs several linear and non-linear regression models(OLS, Lasso, Ridge, SVR, DT) to analyze multiple factors that may affect the demand of shared bicycles in a city. The project structure includes data cleaning, feature engineering, model selection and tuning.

### Data description:

cnt: shared bicycles count, based on hourly data from 2015-01-03 to 2017-01-04.
timestamp: string
t1: hourly temperature
t2: apparent temperature
hum: humidity
wind_speed: float64
weather_code(explained in codes)	
is_holiday: 0 for non-holiday and 1 for holiday
is_weekend: 0 for weekday and 1 for weekend.
season: 0, 1, 2, 3

