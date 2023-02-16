# Cryptocurrency
To get the latest data, go to the previous blog post, where I described how to download it using Cryptocompare API. 
You can also use the data I work within this example.

First, let’s download hourly data for BTC, ETH, and LTC from Coinbase exchange. 
This time we work with an hourly time interval as it has higher granularity. 
Cryptocompare API limits response to 2000 samples, which is 2.7 months of data for each coin.
We are going to analyze closing prices, which are prices at which the hourly period closed. 
We merge BTC, ETH and LTC closing prices to a Dataframe to make analysis easier.
