# fintechproject1
## Tian, Luke, Alvin, Yoheiwaki

## Background
We will aim to create an interactive dashboard that will simulate an invesment proforlio that contains:
- 2 Cryptos
- 2 Stocks 

The Dashboard then provide a financial analisys of the porfolio and project an estimation/prefiction using Monte Carlo model  for 3 years in the future

# Portfolio Analysis  
A dashboard that will take in input of:
- 2 Crypto tickers `crypto_1` and `crypto_2` and the investment amount in AUD for each crypto - `my_aud_crypto_1` and ```my_aud_crypto_2`
- 2 Stocks tickers `stock_1` and `stock_2` and the investment amount in AUD for each stock - `my_aud_stock_1` and `my_aud_stock_2`

#### Collect Crypto Prices Using the `requests` Library

1. Use the `requests` library to fetch the current price in AUSTRALIAN dollars (`AUD`) of `crypto_1` and `crypto_2` using the **Alternative Free Crypto API** 

2. Parse the API JSON response to select only the crypto prices and store each price in a variable.

3. Compute the portfolio value of cryptocurrencies and print the results.

#### Collect Investments Data Using Alpaca: `stock_1` (stocks) and `stock_2` (bonds)

**Important:** Remember to create a `.env` file in your working directory to store the values of your Alpaca API key and Alpaca secret key.

2. Set the Alpac
