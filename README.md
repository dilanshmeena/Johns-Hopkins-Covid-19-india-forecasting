# COVID-19 Analysis and Case Forecasting (Johns Hopkins Data)

Capstone project PRCP-1023 (Healthcare).

## What this project does
- Cleans and analyzes JHU global COVID-19 data
- Forecasts India's daily confirmed cases for the next 30 days
- Compares Naive, Moving Average, ARIMA and Random Forest models
- Gives suggestions to the health department

## Result
ARIMA was the best model (MAE 15,368), about 8 times better than the naive baseline.

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, statsmodels

## Data
JHU CSSE COVID-19 repository: https://github.com/CSSEGISandData/COVID-19
Set `path` in the notebook to your local data folder before running.
