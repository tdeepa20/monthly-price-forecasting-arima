# Monthly Price Forecasting Using ARIMA

## Objective

Forecast average monthly prices using historical time-series data.

## Project Steps

1. Data Loading
2. Date Conversion
3. Missing Value Check
4. Duplicate Check
5. Outlier Detection (IQR Method)
6. Anomaly Detection (Monthly Price Change Analysis)
7. Linear Regression Model Training
8. ARIMA(1,1,1) Model Training
9. Model Evaluation using MAE and RMSE
10. 12-Month Price Forecasting


## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Statsmodels
* Jupyter Notebook

## Model Performance

| Model             |     MAE |    RMSE |
| ----------------- | ------: | ------: |
| Linear Regression | 1795.48 | 2298.74 |
| ARIMA             |  411.06 |  838.61 |

## Conclusion

ARIMA outperformed Linear Regression and was selected as the final forecasting model for predicting future monthly prices.
