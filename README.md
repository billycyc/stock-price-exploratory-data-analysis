# Stock Prices Exploratory Data Analysis
![python](https://img.shields.io/badge/Python-blue) ![pandas](https://img.shields.io/badge/Pandas-green) ![matplotlib](https://img.shields.io/badge/Matplotlib-green)

## What is it?
This project implements the exploratory data analysis (EDA) of the 5 tech stocks in the US stock market from 2017-01-01 to 2022-01-01, namely Apple, Amazon, Google, Meta, Microsoft.  

The charts include line chart, box plot, scatter matrix, heat map, and autocorrelation. 

## Data Source
The stock historical data is obtained from Yahoo Finance website.   
In order to get the data directly with Python, we need to install the *yfinance* package in the environment: 
`!pip install yfinance`. Then the stock data can be downloaded by using *yfinance* package's *download()* function. 
