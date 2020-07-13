# A-Yen-for-the-Future
Time Series Forecasting and Linear Regression Modeling

## Time Series Analysis

### ARMA

* ARMA 5 day forecast

![ARMA_forecast](Images/ARMA_forecast.png)

* Based on the ARMA which had a lower AIC than the ARIMA, I would wait one day before buying the Yen, but I would rerun the prediction before purchase. I would also wait because the ARMA Yield Forecast shows downward movement while the Volatility is increasing.

### ARIMA

* ARIMA 5 day forecast

![ARIMA_forecast](Images/ARIMA_forecast.png)

* The ARIMA forecast for the Yen is the opposite of the ARMA. The ARIMA forecast and increasing value.

### GARCH

* Volatility Forecasting

![GARCH_volatility_forecast](Images/GARCH_volatility_forecast.png)

* Based on the GARCH model, the volatility is steadily increasing

### Conclusions

* I would feel more confident using the ARMA model and waiting a day, but I would spend that day looking at other models.

## Regression Analysis

* First 20 Actual Returns vs Predicted Returns

![Scikit-Learn](Images/Scikit-Learn.png)

* Visually the Scikit_Learn linear regression model does not look usable. The frist spike is predicted to be a dip.

* The Scikit-Learn linear regression model perform better on out-of-sample data compared to in-sample data.

* The Out-of-sample RMSE (0.4152) is less than the In-sample RMSE (0.5659), therefore I beleive this model is not a good fit for this data set. Both numbers are less than 1, but the Returns and Predicted Returns are on a -1 to 1 scale therefore the numbers are not as low as they seem.
