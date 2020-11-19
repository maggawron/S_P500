S&P 500 Analytics by Magdalena Gawron

Aim of this project is to gather the S&P 500 stock price and recommendation data and analysing it. 
Project has been created in Google Colab notebook in Python using BeautifulSoup, YFinance, YahooFinance, Pandas, NumPy and Matplotlib libraries.

Project consits of two parts:
  1. Data Loading (acquired data have been saved in the "Data" folder):
    a) fetching stock tickers and names using webscraping
    b) downloading historical price data and analyst recommendations via Yahoo APIs  
  Link to the saved notebook: https://github.com/maggawron/S_P500/blob/main/S%26P_500_Analytics_data_loading.ipynb
  
  2. Data Analytics - core part:
    a) analysing patterns in daily stock price changes
    b) checking if published recommendations were correct predictors of prices
    c) investigating the impact of ratings on price changes
  Link to the saved notebook: https://github.com/maggawron/S_P500/blob/main/S%26P_500_Analytics.ipynb
