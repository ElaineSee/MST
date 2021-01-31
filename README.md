# MST
Visualise the correlation of Top 30 KLSE Stocks &amp; the KLCI index using Minimum Spanning Tree

## Description
The interactive graph is created using RShiny, visNetwork & igraph in R.

Data: Mid-June'18 to mid-Dec'18 daily closing price of the KLCI constituents (Top 30 stocks by market capitalisation in KLSE). Get the first difference of the log data to remove non-stationarity.

Correlation: Simple Correlation & Exponential Weighted Moving Average (EWMA) Correlation

# Sample output
![alt text](https://github.com/ElaineSee/MST/blob/main/KLCI.png)
