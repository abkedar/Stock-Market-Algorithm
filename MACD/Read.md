# Moving Average Convergence & Divergence
A “moving average” is the average of the asset prices over the “x” number of days/weeks.
# Prerequisites
* Python 3.x
* pandas_datareader
* matplotlib.pyplot
# What is Moving Average Convergence & Divergence?
* The Moving Average Convergence & Divergence(MACD) is one of the most widely used technical indicators.
* A “moving average” is the average of the asset prices over the “x” number of days/weeks.
# How it Works ?
* The term “moving” is used because the group of data moves forward with each new trading day.
* For each new day, we include the price of that day and exclude the price of the first day in the data sequence.
* The most commonly used moving averages are the 5-day, 10-day, 20-day, 50-day, and the 200-day moving averages
# Mathematical Description.
* There are different types of moving averages used for analysis, a **simple moving average (SMA)**, 
  **weighted moving average (WMA)**, **exponential Moving average (EMA)** and **the Smoothed Moving Average (SMMA)**.
* To compute a 20-day SMA, we take the sum of prices over 20 days and divide it by 20.
* To arrive at the next data point for the 20-day SMA, we include the price of the next trading
  day while excluding the price of the first trading day. This way the group of data moves forward.
# 

# **Moving Average Convergence & Divergence(MACD):**
* For Longer we have selected span of 26 days.
* And for Longer we have selected span of 12 days. 

<p align="center"> 
<img src="https://static.anychart.com/images/technical_indicators/macd-macd.png">

# Where the mathematical formula for **Exponential Moving Average** is given as:
* Exponentially smoothed moving average is calculated by adding the moving average of a certain share of the current closing price to the previous value.

<p align="center">
<img src="https://static.anychart.com/images/technical_indicators/ema.png" width="500">

but we have use python code to calculate **Exponential Moving Average**.

# **Signal** is calculated as :

<p align="center">
<img src="https://static.anychart.com/images/technical_indicators/macd-signal.png">

We Have plot both the **Signal** and **Moving Average Convergence & Divergence(MACD)** using **Matplotlib.pyplot** python packages.

# Reference:
* [Technical Analysis: Moving Average Convergence & Divergence(MACD)](https://www.metatrader4.com/en/trading-platform/help/analytics/tech_indicators/moving_average#simple_moving_average)
* [Technical Indicators Mathematical Description](https://static.anychart.com/)