<div align="center">
<h1>Stock Market Trend Prediction Using Time Series Forecasting (ARIMA Model)</h1>

<h2>By Santi Swain</h2>
</div>

---

## 🎯 Project Overview

  The stock market is a complex and dynamic system, influenced by a multitude of factors ranging from global events to company news, economic indicators, and investor sentiment. Predicting stock prices has been a topic of interest for investors, analysts, and researchers for many decades. Accurate predictions can lead to significant financial gains, while inaccurate ones can lead to substantial losses. As such, various mathematical and statistical techniques have been employed to better understand and forecast stock market movements.

This project aims to leverage the power of time series forecasting, specifically using the ARIMA (AutoRegressive Integrated Moving Average) model, to predict stock market price trends. ARIMA is a popular method for analyzing and forecasting time series data as it can capture a suite of different standard temporal structures in time series data.

---

## Problem Statement:

Predict the future closing price of a given stock (in this case, the SPY ETF), based on its historical data, using the ARIMA model. The objectives are:

- Conduct a thorough exploratory data analysis (EDA) to understand the underlying patterns and characteristics of the data.
- Develop a time series forecasting model that can predict future stock prices with reasonable accuracy.
- Evaluate the model's performance against actual stock prices to determine its efficacy and reliability.

---

## 📊 Dataset

The dataset consists of historical stock prices for the SPY ETF, spanning multiple years. It includes features like opening price, closing price, highest price in the day, lowest price in the day, and trading volume.

Collection: The data was sourced from [YahooFinance](https://ca.finance.yahoo.com/quote/SPY/history?p=SPY)

Dataset Timeline: Jan 28, 1993 - Oct 10, 2023

Dataset Structure: The dataset has 7 columns: Date, Open, High, Low, Close, Adj Close, and Volume.
                   There are 7,731 entries, spanning from January 29, 1993, to October 11, 2023.

Missing Values: There are no missing values in any of the columns.

---

## Roadmap

Completed:
- Initial data collection and preprocessing.
- Exploratory Data Analysis (EDA) to understand the underlying patterns and relationships in the data.
- Feature engineering to extract meaningful information and transform data for the model.

Upcoming:
- Model building using the ARIMA technique.
- Hyperparameter tuning and model validation.
- Forecasting future stock prices and evaluating model performance against actual prices.
- Potentially exploring other models and techniques for comparison.

---

## Learnings

- The importance of thorough EDA in time series analysis.
- The challenges of making a time series stationary.
- The nuances of feature engineering in time series data.
