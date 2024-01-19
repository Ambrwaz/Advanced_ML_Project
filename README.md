# Advanced_ML_Project

## Introduction
This project aims to explore the state-of-the-art in financial time series forecasting with the ambition of comparing both traditional and more recent models. The underlying objective is to delve deeply into the application of neural networks in the realm of business.\\

For the aforementioned purposes, we decided to focus our work on the time series of Bitcoin's price, considering how famous of an instrument it is and for its great mathematical properties.\\

The current projet is divided in a few sections: we first introduce the data and the mathematical framework related to time series (stationarity and mixing assumptions); we then explore some of the traditional ways of handling financial time series (ARIMA models, GARCH models, etc.) before implementing Deep Learning methods (LTSM, GRU neural networks).

## Data
The data we used in the project consists in 30 days worth of BTC-USD (bitcoin, in \$) historical prices at 1-min intervals. We retrieved it using the Yahoo Finance API over the period 02/11/2023 - 01/12/2023.


## Deep Learning
All the cells concerning Deep Learning in the notebook are original.
In order to use the models we trained, unzip the trained_models file in the same folder as the notebook.
Every section needed to be run are specified in the notebook.
### Data 
