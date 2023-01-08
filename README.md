# Hourly-Weighted-Average-Price-Volumes-of-Bitcoin-for-each-of-the-available-exchanges
The objective is to calculate the hourly Weighted Average Price Volumes of Bitcoin, for each of the exchanges available.

It will be important to store the final result as a Pandas DataFrame.
This DataFrame must therefore, logically:

• Be indexed by dates

• Have one line per hour of the data time interval provided

• Contain one column per exchange containing the hourly VWAP on this exchange

• Contain a “global” column containing the VWAP relating to all trades, regardless of the exchange

