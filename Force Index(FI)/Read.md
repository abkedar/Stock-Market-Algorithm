# Force Index(FI)
* Force Index show that their is positive increase in Trend when as new peak is achieve.
* And Show sell when the index becomes positive during the decreasing tendency.

# Prerequisites
* Python 3.x
* pandas_datareader
* matplotlib.pyplot
* datetime

# What is Force Index(FI) ?
* In other words index measures the Bulls Power at each increase, and the Bulls Power at each decrease.
* The force index uses price and volume to determine the amount of strength behind a price move.
* The index is an oscillator, fluctuating between positive and negative territory.

# How it Works ?
* Compile the most recent closing price (current), the prior period's closing price, and the volume for the most recent period (current volume).
* Calculate the one-period force index using this data.
* Calculate the exponential moving average using multiple one-period force index calculations. 
  For example, to calculate a force index (20) will require at least 20 force index (1) calculations.
* Continually repeat the steps after each period ends.

# Mathematical Description.
* Below images contains mathematical description of all technical indicators formula.
* Force Index is calculated in three step as follow:
    1. Current Closing Price.
    2. Prior close price.
    3. Volume force index.
    4. Exponential moving average.
    5. Force index.

# **Current Closeing Price:** 

* What is **Current Closing Price** & **Prior Closing Price**:
* Closed price will be the price on which market is closed or last trade done that day,and the current price will be next 
  opening price or its totally depend at what time you are watching the the stock price. After market close ,close price 
  and current price can be considered as same. Watch the below video to understand price movements. 

[Current Closing Price](https://img.youtube.com/vi/th7quaNj74c/0.jpg)

# Calculate the **Volume Force Index**:

* Volume Force Index mean number of stocks sold or buy on that particular day.

# Formula for **Exponential moving average.**:
* The mathematical formula for Exponential moving average is given as:

<p align="center">
<img src="https://static.anychart.com/images/technical_indicators/adl.png" width="550">

# Formula for **Force Index** is given as:

### *Force Index(1) = {Close (current period)  -  Close (prior period)} x Volume*

### *Force Index(n) = n-period EMA of Force Index(1)*

We Have plot the **Force Index** graph using **Matplot** Libraries python packages.

# Reference:
* [Technical Analysis: Force Index](https://school.stockcharts.com/doku.php?id=technical_indicators:force_index)
* [Mathematical Formula](https://www.investopedia.com/terms/f/force-index.asp#:~:text=The%20force%20index%20is%20a,the%20price%20of%20an%20asset.&text=The%20force%20index%20uses%20price,between%20positive%20and%20negative%20territory.)
* [Technical Indicators Mathematical Description](https://static.anychart.com/)