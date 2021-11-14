# Capstone Project: Predicting BTC price using basic prediction algorithms

## Problem Statement
While asset pricing is a relatively mature subject and there have been various machine learning researches applied within this domain, especially on the pricing of bonds and equities, cryptocurrency is an emergent field with huge potentials to explore.
There are two main disciplines to analyze assets: Fundamental and Technical. Fundamental analysis is a method of evaluating the intrinsic value of an asset and analysing the factors that could influence its price in the future. Technical analysis is a trading discipline employed to evaluate investments and identify trading opportunities by analyzing statistical trends gathered from trading activity, such as price movement and volume. Due to the special characteristic of cryptocurrency, technical analysis is deemed to be the appropriate approach rather than fundamental analysis. This project aims to apply a variety of machine learning methods on a comprehensive set of market-predictive features.


## Datasets and inputs
The dataset is obtained from Binance using python-binance API. Trading features include price, volume, open, high, low values present in the dataset.


## Project design
The workflow of this project follows the following order:
1. Getting the data with predefined scope
2. Exploring the data
  a. Data structure
  b. Data dimensions
  c. Statistical Summary
  e. Test for stationarity
3. Data Preprocessing
  a. Preprecess features
  b. Identify Feature and Target columns
  c. Data Cleaning
  d. Training and Validation data split
  e. Feature Scaling
4. Build
  a. Linear Regression - baseline model
  b. GRU
  c. LSTM
5. Model tuning
6. Conclusion
