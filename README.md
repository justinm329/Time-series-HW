# Time-Series-Conclusions


## Time Series Analysis Conclusions

### Based on your time series analysis, would you buy the yen now?
* Based on this time series analysis I would buy the yen now since it would increase in price based on the ARIMA and ARMA models and the GARCH models infers that it will increase in volitility over the next 5 days. 

### Is the risk of the yen expected to increase or decrease?
* The risk of the yen is expected to increase based on the GARCH model.

### Based on the model evaluation, would you feel confident in using these models for trading?
* I would not feel confient trading with these models, the P values for the first 2 were way above 0.05 which tells me they were not accurate. The GARCH model however was accurate so I would go back and fix the other two models if I were to use these for predictions. 

* I went back to the ARMA and ARIMA model and plotted the pacf to give me a better idea of the auto correlation. The number of lags the assigment told me to use differed from what the pacf suggested I use. The pacf only had one significant data point which would let me know to fill in the order as (1,1) whereas the assingment told me to use (2,1). When I changed the order the pvalues were significatly lower, this would tell me that this is a better model to use for  predicting the future value of the yen. 


## Regression_Analysis

### What were your conculsions based on the regression analysis? 
* RMSE is the measure of how far our line of best fit is to the data points. The lower the RMSE the better it is at making predictions. In this case our RMSE data for our out of sample performance was .41 where it was 0.59 for our in sample data. This tells me that our model was better at predicting future data of the yen compared to the prediciting the past data. This is a strange becuase the past data should have a lower RMSE since it has the correrct answers. None the less this model was better at prediciting the future values since it had a lower RMSE.