# Overview

This project involves the analysis and prediction of Netflix (NFLX) stock prices using historical data. Leveraging the yfinance Python package, I collected and cleaned the data, and developed predictive models using ARIMA and LSTM to forecast future stock prices. This project aims to provide insights into stock price trends and evaluate the effectiveness of different time-series forecasting models.

## Table of Contents
1. Project Motivation
2. Data Collection
3. Data Cleaning
4. Exploratory Data Analysis
5. Modeling
    - ARIMA Model
    - LSTM Model
6. Results
7. Conclusion
   
## Project Motivation
The stock market is a complex system influenced by various factors, making it a challenging yet fascinating subject for time-series analysis. This project was undertaken to:

 - Gain hands-on experience with time-series forecasting techniques.
 - Compare traditional statistical models with modern machine learning approaches.
 - Provide actionable insights for potential investors and stakeholders.

## Data Collection
The historical stock price data for Netflix (NFLX) was collected using the yfinance Python package. This package provides a convenient interface to download stock data from Yahoo Finance.

## Data Cleaning
The collected data was cleaned to handle missing values, remove anomalies, and ensure the dataset was suitable for analysis and modeling. Key steps included:

 - Removing outliers based on statistical analysis.
 - Normalizing the data for model compatibility.

## Exploratory Data Analysis
I conducted an exploratory data analysis (EDA) to understand the data's underlying patterns and trends. This included:

 - Visualizing stock price trends over time.
 - Analyzing statistical properties of the dataset.
 - Identifying seasonal and cyclical patterns in the data.

##  Modeling
## ARIMA Model
The ARIMA (AutoRegressive Integrated Moving Average) model is a traditional statistical approach for time-series forecasting. I optimized the model parameters (p, d, q) using grid search and evaluated the model's performance on the test set.

## LSTM Model
The LSTM (Long Short-Term Memory) model is a type of recurrent neural network (RNN) designed to capture long-term dependencies in sequential data. I built and trained an LSTM model using TensorFlow/Keras and evaluated its performance on the test set.

## Results
Both models were evaluated based on their predictive accuracy and ability to capture trends in the stock prices. The results demonstrated that:

 - The ARIMA model performed well for short-term predictions.
 - The LSTM model showed superior performance in capturing complex patterns and long-term trends.

## Conclusion
This project successfully demonstrated the application of ARIMA and LSTM models for stock price prediction. While the ARIMA model is effective for simpler, short-term forecasts, the LSTM model excels in handling more complex, long-term predictions. Both models have their strengths and can be valuable tools for different forecasting scenarios.
