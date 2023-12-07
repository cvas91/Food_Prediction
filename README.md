# Comparing ML models on food price prediction
Link to the Dataset: https://ca.finance.yahoo.com/commodities/ 

## Dataset Description:
YahooFinance.com provides daily and free accessible historical data of commodities traded daily on the US capital markets. The datasets chosen for this project are 10 food commodities composed of: Corn, Oat Wheat, Rice, Soybean, Cocoa, Coffee, Sugar, Hogs, and Cattle. Each dataset (food commodity) contains features like the Open, High, Low, Close, Adj. Close prices, as well as the Volume traded each day. The period considered is almost 23 years of daily data for each of the 10 datasets, ranging from January 2000 to November 2023, aggregating a total of more than 50.000 samples. 

## Task Goal:  
Compare the performance of machine learning models in the prediction of food commodities prices. 

## Task Description:
Given the increases in food prices in the post-pandemic era and recent international conflicts, this project aims to find the best machine learning models by applying Linear Regression, Long Short-Term Memory (LSTM), and Extreme Gradient Boosting XGB Regressor to time series daily data of the last 23 years. These models will predict the Close price for each commodity based on features like Open, High, Low, Adj. Close prices, and Volume as well as seasonal features year, quarters or months. The model comparison will be based on metrics MAE, MSE, RMSE, RMSLE, and R-squared.

## Python Code:
See Code_Group1_DS_1.ipynb [https://github.com/cvas91/Food_Prediction/blob/main/Code_Group1_DS_1.ipynb] for full project development.
