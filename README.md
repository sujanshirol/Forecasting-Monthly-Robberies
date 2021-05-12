# Forecasting Monthly Armed Robberies in Boston
Several methods and techniques of time series forecasting are used to forecast whether robberies in Bosted will increase or decrease in upcoming years. Which will help government and police department to take measure accordingly.

![image](https://user-images.githubusercontent.com/71747522/117823611-499a9d80-b28b-11eb-9267-a15d933f545c.png)


1. Splitting dataset into data and validation
2. Transforming date column
3. Data analysis
4. Dickey-Fuller test for stationarity
5. ACF PACF plots
6. Defferencing to make the series stationary
7. Train-test split
8. Box-Cox transformation
9. Building ARIMA model
10. Hyperparameter tuning
11. Rolling forecasting to capture random variation
12. Exponential Smoothning
13. Validation
14. Forecasting for next 1 year

## Evaluation metric
Mertic will be Root Mean Sqaure Error(RMSE) and Mean Absolute Percentage Error(MAPE). Although, we will be looking at both metrics the main goal will be to get the MAPE below 10%.

![image](https://user-images.githubusercontent.com/71747522/117994560-445a5300-b35e-11eb-91c6-dc12fe990e99.png)


## Trend in series
![image](https://user-images.githubusercontent.com/71747522/117823692-60d98b00-b28b-11eb-88ca-d63fa1de38d0.png)

## Dickey-Fuller test
Null hypothesis:Series is not stationary<br>
Alternate hypothesis: Series is stationary<br>
ADF Statistic: 0.797485<br>
p-value: 0.991595<br>
Critical Values:<br>
	1%: -3.50270<br>
	5%: -2.89316<br>
	10%: -2.58364<br>
  
## Forecasting
![image](https://user-images.githubusercontent.com/71747522/117823901-9a11fb00-b28b-11eb-997f-a1b135cf13c6.png)

## Conclusion
**It is forecasted that armed robberies are going to be increased in the next one year. Government and police has to take measure accordingly by imposing strict measures and deploying more man-force for patrolling**\

![image](https://user-images.githubusercontent.com/71747522/117994958-8daaa280-b35e-11eb-984b-e26d639d7d7b.png)



