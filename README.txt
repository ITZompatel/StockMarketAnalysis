# Stock Market Analysis and Prediction 

##Project Overview
This project analyzes historical stock prize for "Tata Consultancy Services (TCS) and builds a predictive model using Python.

The aim is to understand trends in stock market using moving averages and volatility analysis

Predicting the future stock prices with a linear regression model 

--

##Tools and Libraries
The project utilizes the following tools and lib-

- yfinance
- pandas
- matplotlib
- scikit-learn

--

## Features
1. Data Collection:
   - Fetches historical stock data (2015–2025) for TCS using `yfinance`.
2. Exploratory Data Analysis (EDA):
   - Plots historical trends in closing prices.
   - Analyzes daily returns to assess volatility.
3. Feature Engineering:
   - Creates features like 50-day and 200-day moving averages.
   - Computes volatility as a rolling standard deviation of daily returns.
4. Predictive Modeling:
   - Trains a "Linear Regression model" to predict stock prices based on the engineered features.
5. Evaluation:
   - Calculates "Mean Squared Error (MSE)" and **Root Mean Squared Error (RMSE)** to evaluate model performance.

--

##Results
-RMSE - 99.26
-The model predicts stock prices with reasonable accuracy, capturing overall market trends 

## How To Run

Install Python with following libraries:
-pandas
-matplotlib
-scikit-learn
-yfinance


