# Relative Strength Index(RSI)
* RSI is used to measure speed and change of the price fluctuations. 
* This indicator provides an idea of the security’s recent performance in the stock market. It measures the strength of the stock in the range of zero to a hundred.
# Prerequisites
* Python 3.x
* pandas_datareader
* matplotlib.pyplot
* datetime
# What is Relative Strength Index(RSI) ?
* the name suggests, tells us the relative strength of the asset. 
* In other words, the RSI tells us how well the stock is performing (or not) with respect to itself.
# How it Works ?
* RSI works as a reference when you want to gauge if the market is going through a bullish or bearish trend.
* It show a graph which have number on y-axis ranging from 10, 30, 50, 70, 90.
* An indicator whose stock indicate above 70 range it mean overbought of stock and below 30 indicates oversold 
  of stock holds true for most of the cases, there are others who insist that it can be held true for values above 66.6 and below 33.3 as well.
* The most commonly used moving averages are the 5-day, 10-day, 20-day, 50-day, and the 200-day moving averages
# Mathematical Description.
* Below images contains mathematical description of all technical indicators formula.
* Relative Strength Index is calculated in three step as follow:
    1. Upward change (U) or downward change (D)
    2. Then two averages one for upward change and another for downward change.
    3. Then comes RSI formula.

# **Upward changes and Downward change in stock price:** 

* Upward change (U) or downward change (D) sequences are calculated:
<p align="center"> 
<img src="https://static.anychart.com/images/technical_indicators/rsi-u-d.png">

# Calculate the **Moving Average** of **Upward Change & Upward Change**:

* The mathematical formula for Moving average of upward and downward change is given as:
<p align="center">
<img src="https://static.anychart.com/images/technical_indicators/rsi-mau.png">

# Formula for **Simple Moving Average"":
* The mathematical formula for Moving average of upward and downward change is given as:

<p align="center">
<img src="https://static.anychart.com/images/technical_indicators/rsi-rsi.png">

We Have plot both the **Upward changes and Downward change** and **Moving Average of Upward & Downward change** using **Matplotlib.pyplot** python packages.

# Reference:
* [Technical Analysis: Moving Average Convergence & Divergence(MACD)](https://www.metatrader4.com/en/trading-platform/help/analytics/tech_indicators/moving_average#simple_moving_average)
* [Technical Indicators Mathematical Description](https://static.anychart.com/)