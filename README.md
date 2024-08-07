# TrendWatch-S-P-Market-Time-Series-Analysis

S and P 500 Stock Market Analysis


Context:


Stock market data can be interesting to analyze and as a further incentive, strong predictive models can have large financial payoffs. The amount of economic data on the web is seemingly endless. A large and well-structured dataset on a wide array of companies can be hard to come by. Here I provide a dataset with historical stock prices (last 5 years) for all companies currently on the S&P 500 index.


The data is presented in a couple of formats to suit different individual's needs or computational limitations. I have included files containing 5 years of stock data (in the all_stocks_5yr.csv and corresponding folder).


The folder individual_stocks_5yr contains files of data for individual stocks, labeled by their stock ticker name. The all_stocks_5yr.csv contains the same data, presented in a merged .csv file. Depending on the intended use (graphing, modeling etc.) the user may prefer one of these given formats.

All the files have the following columns:
Date - in format: yy-mm-dd

Open - price of the stock at market open (this is NYSE data so all in USD)

High - Highest price reached in the day

Low Close - Lowest price reached in the day

Volume - Number of shares traded

Name - the stock's ticker name
