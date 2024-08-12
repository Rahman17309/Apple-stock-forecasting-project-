# Apple stock forecasting project

Check out the demo video:

[![Apple Stock Forecasting 2012 - 2020](https://ytcards.demolab.com/?id=r2wZKC7ocJk&title=Apple+Stock+Forecasting+Model&lang=en&timestamp=1723401000&background_color=230d1117&title_color=23ffffff&stats_color=%23dedede&max_title_lines=16width=250&border_radius=5&duration=311 "Apple stock forecasting 2012 - 2020")](https://www.youtube.com/watch?v=r2wZKC7ocJk)


### Business Objective 

The objective of this project is to predict the Apple stock market price for the next 30 days. The dataset contains daily Open, High, Low, and Close prices of Apple stock from 2012 to 2019. This project aims to:

Split the last year of data into a test set and build a model to predict stock prices.

Identify short-term and long-term trends.

Understand the impact of external factors or significant events on stock prices.

Forecast stock prices for the next 30 days.

## Table of Contents:

1. Dataset
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Model Building

     a. ARIMA

     b. SARIMA

     c. LSTM

     d. Prophet

     e. Exponential Smoothing

5. Model Evaluation
6. Forecasting
7. Results
8. Conclusion


## Dataset

The dataset contains daily stock prices of Apple Inc. from 2012 to 2019. The columns in the dataset include:

Date: The date of the stock price.

Open: The opening price of the stock on the given date.

High: The highest price of the stock on the given date.

Low: The lowest price of the stock on the given date.

Close: The closing price of the stock on the given date.

## Data Preprocessing

Load the Dataset: Import the dataset and load it into a Pandas DataFrame.

Handle Missing Values: Check for and handle any missing values in the dataset.

Feature Engineering: Create additional features such as moving averages and stock price differences.

Scaling: Scale the features using MinMaxScaler for models that require scaled input data.

## Exploratory Data Analysis (EDA)

Perform EDA to gain insights into the dataset:

Visualize Stock Prices: Plot the Open, High, Low, and Close prices over time.

Moving Averages: Calculate and plot moving averages to identify trends.

Correlation Analysis: Analyze the correlation between different features.

Seasonality: Check for seasonal patterns in the stock prices.

## Model Building

### ARIMA

ARIMA (AutoRegressive Integrated Moving Average) is a popular time series forecasting method.

Perform stationarity tests and determine the order of differencing required.

Use ACF and PACF plots to determine the order of AR and MA components.

Fit the ARIMA model and make predictions.

### SARIMA

SARIMA (Seasonal ARIMA) incorporates seasonality into ARIMA models.

Identify seasonal patterns and determine the seasonal order (P, D, Q, m).

Fit the SARIMA model and make predictions.

### LSTM

LSTM (Long Short-Term Memory) networks are a type of RNN suitable for sequence prediction.

Prepare the data for LSTM by creating sequences of input features.

Build and train the LSTM model.

Make predictions using the trained LSTM model.

### Prophet

Prophet is a time series forecasting tool developed by Facebook.

Fit the Prophet model on the historical stock price data.

Make predictions using the Prophet model.

Exponential Smoothing

Exponential Smoothing methods are used for time series forecasting.

Fit models like Holt-Winters to the stock price data.

Make predictions using the fitted models.

### Model Evaluation

Evaluate the performance of each model using the following metrics:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

Compare the models based on their performance on the test set.


## Forecasting

Use the best-performing model to forecast the stock prices for the next 30 days.

Visualize the forecasted prices along with the historical data.

## Results

Summarize the results of the model evaluation and forecasting. Highlight the best-performing model and the forecasted stock prices for the next 30 days.


## Conclusion

Discuss the short-term and long-term trends identified.

Analyze the impact of external factors or significant events on the stock prices.

Provide insights and recommendations based on the forecasting results.
