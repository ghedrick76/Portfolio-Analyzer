# Portfolio Analyzer Application

An application to analyze a stock or portfolio of stocks. The user can choose their tickers and run different analyses on them, as well as perform a Monte Carlo simulation on a basket of stocks.


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


# Installation

### Clone Repository
git clone https://github.com/ghedrick76/Portfolio-Analyzer.git


### Install Dependencies
Listed above are the relevant dependencies.  Jupyter Lab is also required.

### Start Application

The application can be run by navigating to the Portfolio-Analyzer Directory in the terminal.  Type jupyter lab to run the notebook!  You can input your stocks and the analyses will be run.





