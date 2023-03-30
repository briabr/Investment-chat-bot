# Project 2- Model Performance Comparison on Investments
Contributers:  Bria, Anurag, Bryan and Evelyn.

Objective:

In this project we wanted to know which machine learning models could best perform in forecasting stock prices and returns. Specifically in Bitcoin and the S&P 500 for the past 5 years. This is in an effort to provide recommendations for investors on their investments.


Data and clean up:

For simplicity, CSV files were downloaded from Kaggle and Data was cleaned using the data frame function.

Models and techniques used to evaluate performance:

We used Prophet, Arima and Neural Network for analysis and forcecasting.

Prophet was used, as an effort to to pick up trends and changes over time. Arima, which stands for Autoregression Integrated Moving Average, uses multiple different variables to analyze a time series. Autoregression makes a comparision between data of the past and present, while the Moving Average shows the comparison between the past and present forecast errors. The most elaborate and complex Machine Learning model we used are Neural Networks, that takes into consideration more complex relationships to determine forecasts.

In order to determine the the accuracy of the models, Cross Validation was used when analyzing Prophet and RMSE (Root Mean Squared Error) for Prophet, Arima and Neural Network. Cross Validation measures the errors in forecasting through past data. In RMSE, the standard deviation shows just how far off the predicted data points are from the regression line. After these techniques were applied, our conclusion was based off of the lowest value of the RMSE and

