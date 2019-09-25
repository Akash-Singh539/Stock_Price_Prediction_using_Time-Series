# Stock_Price_Prediction_using_Time-Series

In this project we have used Time series analysis for doing stock price forecasting and the dataset was taken from https://www.quandl.com/data/NSE/TATAGLOBAL-Tata-Global-Beverages-Limited.

# Methods used for Time-series forcasting:-

1) Auto-ARIMA: - it was used instead of ARIMA because its hard to tune the hyper parameters, hence we have used auto-arima model to provide the best suitable model for the dataset. 
The model has captured a trend in the series, but does not focus on the seasonal part. In the next section, we will implement a time series model that takes both trend and seasonality of a series into account.

2) LSTM: - LSTMs are widely used for sequence prediction problems and have proven to be extremely effective. The reason they work so well is because LSTM is able to store past information that is important, and forget the information that is not and it can be seen from the output that this model is capable of capturing the seasonal problem in the series.
