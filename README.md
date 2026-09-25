# Time-Series Demand Forecasting Using ARIMA

## Project Overview

This project focuses on forecasting daily demand using time-series analysis and the ARIMA(1,2,1) model.

## Research Question

Can historical daily demand data be used to forecast future demand using the ARIMA time-series forecasting model?

## Objectives

- Analyze historical daily demand data.
- Check the stationarity of the demand series.
- Apply differencing where required.
- Develop an ARIMA forecasting model.
- Evaluate the model using MAPE and RMSE.
- Generate future demand forecasts.

## Methodology

The project follows these steps:

1. Data preprocessing
2. Exploratory Data Analysis
3. Stationarity testing using the Augmented Dickey-Fuller test
4. Differencing
5. ARIMA model development
6. Train-test evaluation
7. Future demand forecasting

## Model

**ARIMA(1,2,1)**

- p = 1
- d = 2
- q = 1

## Model Performance

| Metric | Result |
|---|---:|
| MAPE | 7.41% |
| RMSE | 14.23 |

## Future Forecast

A 30-observation future demand forecast was generated using the fitted ARIMA model.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn
- Google Colab

## Project Files

- **Notebook** – Complete Python implementation and analysis
- **Dataset** – Original dataset used for the analysis
- **Actual vs Predicted Graph** – Model prediction evaluation
- **Future Forecast Graph** – 30-observation future demand forecast
- **Research Report** – Final research report

## Conclusion

The ARIMA-based forecasting approach provided reasonably accurate demand predictions and can support data-driven demand planning and decision-making.# time-series-demand-forecasting-arima
Time-series demand forecasting using ARIMA(1,2,1)
