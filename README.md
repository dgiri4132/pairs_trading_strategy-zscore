#Highly correlated Stock pair finder with Z-score Analysis
This Python project helps users indenfiy the top correlated stock pairs form makor stock exchanegs in a given time frame abd z-score analysis to explore potential mean reverting opportunities for pairs trading strategies.

#Features
-Choose from 7 major global indices
-Automatically scrapes component tickers from Wikipedia
-Downloads historical data(from start date to end date) using yfinance
-Filters and removes:
  - Delisted or missing stocks
  - Duplicate ticekrs of the same company
-Computes pairwise correlations between stock returns
-Displays top 5 most highly correlated stock pairs
-Performs z-score analysis on the most correlated pair to detect trading signals
-Avoids lookahead bias during the simulation.

#Technologies used
- Python 3
- pandas
- yfinance
  
