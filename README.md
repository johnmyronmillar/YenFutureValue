# A-Yen-for-the-Future
Time Series Forecasting and Linear Regression Modeling

## Time Series Analysis

Use the results of the time series analysis and modeling to answer the following questions:

1. Based on your time series analysis, would you buy the yen now?
2. Is the risk of the yen expected to increase or decrease?
3. Based on the model evaluation, would you feel confident in using these models for trading?

## Regression Analysis

* First 20 Actual Returns vs Predicted Returns

![Scikit-Learn](Images/Scikit-Learn.png)

* Visually the Scikit_Learn linear regression model does not look usable. The frist spike is predicted to be a dip.

* The Scikit-Learn linear regression model perform better on out-of-sample data compared to in-sample data.

* The Out-of-sample RMSE (0.4152) is less than the In-sample RMSE (0.5659), therefore I beleive this model is not a good fit for this data set. Both numbers are less than 1, but the Returns and Predicted Returns are on a -1 to 1 scale therefore the numbers are not as low as they seem.
