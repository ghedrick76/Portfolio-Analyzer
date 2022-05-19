Portfolio Analyzer Application

Project 1 for UNCC FinTech Boot Camp


Description


The user can input any five tickers that they select, and it will return statistics on their portfolio.
They can also input the quantity of their tickers to calculate the portfolio value.
Users can choose to save a copy of the portfolio DataFrame they create to a .csv file located in the "Resources" folder.
The application then gathers data from the S&P 500, DJI, and NASDAQ from a .csv file and plots them.

Finally, a Monte Carlo simulation is run on the indexes and the user's portfolio to determine whether or not their portfolio will outperform the market.
 



Required Libraries



os
requests
json
pandas
dotenv
alpaca_trade_api
pathlib
MCForecastTools 
hvplot
dateutil.relativedelta


This application saves a copy of your portfolio to a csv in "Resources".

