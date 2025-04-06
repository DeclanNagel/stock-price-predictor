# Stock Price Prediction

## Project Overview

This project focuses on predicting stock price movements using historical data and machine learning techniques. The goal is to predict future price movements of stocks based on historical data like stock prices and volume, using a Random Forest Classifier.

The project includes various machine learning features such as rolling averages, price ratios, and backtesting to evaluate the model's performance.

---

## Key Features:
- Stock Price Prediction: Predicts the future price movements based on historical stock data (open, close, high, low prices, and volume).
- Rolling Averages and Features: Calculates rolling averages and technical indicators to generate new features.
- Backtesting: Implements a backtesting strategy to evaluate model performance over historical data.

---

## Model Performance:
- Final Precision: 64.26%

## Attempt at Enhancing Precision Score with Sentiment Analysis

In the file sentiment_analysis-2.ipynb, I attempted to integrate sentiment analysis features into the model used in historical_data_predictions.ipynb to see if it would enhance the precision score. Unfortunately, when testing the sentiment analysis model, the precision score was only 0.33. I believe the low precision score was due to the limited number of news sentiment entries available for prediction. This issue arose because I was only able to extract sentiment data from recent date ranges, which resulted in the model having only three entries to predict from. I attempted to expand the date range by acquiring more data; however, the Alpha Vantage free tier restricts the amount of historical data I could access. As a result, I was unable to successfully integrate sentiment analysis into the historical_data_predictions model under these constraints.


