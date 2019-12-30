# Quick Foray into Forecasting on Time Series Data




# Description
For a given Time Series Dataset, how can it be represented through different models. 

# Project Purpose
The purpose of this project is to give a quick introduction into handling time series data. Since modeling time series are very similiar, an individual learning the basic tools to process the data will have an easier time processing other datasets. The data used in this project will be Apple Stocks. This will be reflected in the results section of this page.
### Table of Contents
* Part 1: Simple Graph Representation
* Part 2: Linear and Polynomial Regression
* Part 3: Moving Average
* Part 4: XGBoost
* Part 5: Keras LSTM

# Installation 
- matplotlib
- pandas
- os
- numpy
- sklearn
- keras
- tensorflow
- xgboost

# Documentation
The actual processing code is detailed in python notebook. In this notebook, the code is chunked and commented 

# Results
* Linear Regression: RMSE = 14.73
* Polynomial Regression: Power = 8: RMSE = 9.15
* Moving Average: Window = 14: Power = 3: RMSE = 0.85
* XGBoost: Tree Count = 65: Tree Depth = 13: Gamma = .3: RMSE = 1.11
* LSTM: Window = 2: Epoch = 36: RMSE = 1.65


# Inspiration
I utilized the following sources:
* [Data](https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs/data#aac.us.txt)
* [Source 1](https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/)
* [Source 2](https://realpython.com/linear-regression-in-python/)
* [Source 3](https://towardsdatascience.com/a-beginners-guide-to-linear-regression-in-python-with-scikit-learn-83a8f7ae2b4f)

