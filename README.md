# Stock-Market-analysis-using-Deep-Learning
* Stock Prediction
In this task, the future stock prices of State Bank of India (SBIN) are predicted using the LSTM Recurrent Neural Network. Our task is to predict stock prices for a few days, which is a time series problem. The LSTM model is very popular in time-series forecasting, and this is the reason why this model is chosen in this task. The historical prices of SBIN are collected automatically using the nsepy library of python. We have used 6 years of historical price data, from 01.01.2013 to 31.12.2018.

This data set contains 1483 observations with 12 attributes. After preprocessing, only dates and OHLC (Open, High, Low, Close) columns, a total of 5 columns, are taken as these columns have main significance in the dataset. The LSTM model is trained on this entire dataset, and for the testing purpose, a new dataset is fetched for the duration between 01.01.2019 to 18.09.2019. The stock prices for this new duration will be predicted by the already trained LSTM model, and the predicted prices will be plotted against the original prices to visualise the model’s accuracy.

## Implementation
Before proceeding further, make sure that you have installed TensorFlow and nsepy libraries. TensorFlow will be used as a backend for LSTM model, and nsepy will be used to fetch the historical stock data. 



# Stock-Market-analysis-using-Machine-Learning
Stock market analysis using quandl

