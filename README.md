# Stock_Prediction
## Introduction 
The act of attempting to anticipate the future value of a business stock or other financial instrument traded on an exchange is known as stock market prediction. A successful forecast of a stock's future price could result in a large profit. Stock prices, according to the efficient-market theory, represent all currently accessible information, and any price fluctuations that are not based on newly revealed information are thus fundamentally unpredictable.

Stock Price Prediction using machine learning helps us discover the future value of company stock and other financial assets traded on an exchange.Predicting the market is challenging because the future is inherently unpredictable.Multiple (macro and micro) aspects, such as politics, global economic conditions, unforeseen events, a company's financial performance, and so on, make accurate stock price forecast extremely difficult.

We are using Long Short-Term Memory (LSTM) method to create a Machine Learning model to forecast  the price of the share of a company. Long-term memory (LSTM) is a deep learning artificial recurrent neural network (RNN) architecture.

## Dataset
The datasets used in this project is 7 year stock prices of companies such as SBIN.This datasets are used to train and test the LSTM model.These datasets are directly fetched using yfinance.yfinance is an open-source tool that uses Yahoo's publicly available APIs, and is intended for research and educational purposes.

The dataset mainly includes : Date, Open, High, Low, Close, Adj Close and Volume

The Close price of the stock on a daily basis except weekends are considered for the training and testing purposes.The Close price for the first 5 years are used for the training purpose while the rest 2 years are use for testing purpose of the model.
The dataset can be easily modified by the user according to their preference.The number of years taken into consideration can be increased or decreased.The more dataset considered,better the results.

## Implementation
The implementation part consist of several steps :- 

--> Loading the data

--> Preparing or preprocessing the data

--> Building the model

--> Loading the test data

--> Making Predictions on test data

--> Plotting the test predictions

--> Predicting the next day closing price

--> Computing the R-squared (R^2) and Adjusted R-squared (R^2) in percentage

--> Computing the Mean Absolute Error(MAE)

## Sample
### Stock - SBIN
![](sample/SBIN.jpg)
