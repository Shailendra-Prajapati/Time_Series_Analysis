In this notebook we will be looking at data from the stock market, particularly some technology stocks. We will learn how to use pandas to get stock information, visualize different aspects of it, and finally we will look at a few ways of analyzing the risk of a stock, based on its previous performance history. We will also be predicting future stock prices through a Long Short Term Memory (LSTM) method!

Prophet is Facebook's library for time series forecasting. In my opinion, Prophet works best with datasets that are higely influenced by seasonality (electricity bills, restaurant visitors etc.) However, I wanted to show the simplicity of using Prophet for simple forecasting which is the main aim of this part


We'll be answering the following questions along the way:
    1.)What was the change in price of the stock over time?
    2.) What was the daily return of the stock on average?
    3.) What was the moving average of the various stocks?
    4.) What was the correlation between different stocks'?
    5.) How can we attempt to predict future stock behavior? (Predicting the closing price stock price of APPLE inc using LSTM)
    6.) How we can implement FBProphet to find the trend and predict the closing price
    
For the first four question dataset has been downloaded from the Yahoo using the Yfinance Library for the last one year from the current date.
For the model prediction I have taken dataset from the 2012-01-01 to till using the Pandas DataReader library which is used to fecth the data from the Yahoo

