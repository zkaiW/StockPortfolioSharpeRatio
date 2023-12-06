# Portfolio optimization using Sharpe ratio.
This repository contains a Jupyter notebook with an investment strategy for stock portfolios, although it could be applied to other securities and assets.


## Intro

Sharpe ratio measures the performance of an investment such as a security or portfolio compared to a risk-free asset, after adjusting for its risk. Investors prefer portfolios with a higher Sharpe ratio, as it indicates that either higher returns or lower volatility.

## Stocks used
In this project, a portfolio containing four stocks were used : Apple, Google, Tesla and Nio.

## Obtaining data
Stock data was obtained using yahoo finance API, by importing the yfinance package.

```python
import yfinance

# obtaining stock data of Amazon from 10-09-2019 to 09-10-2019
df = yfinance.download('AMZN', start='2019-09-10', end='2019-10-09')

```

## Method

Define functions to generate mean daily returns and a covariance matrix for our stocks
Define function to randomly weight proportions of each stock in a portfolio and calculate the portfolio's risk-adjusted return (Sharpe ratio) and variance over a specified period of time
Use Monte-Carlo method to find weighting of stocks to maximize Sharpe ratio and minimize volatility


## Plot the portfolios, green star for max Sharpe, red for min Sharpe
# Portfolio optimization using Sharpe ratio.
This repository contains a Jupyter notebook with an investment strategy for stock portfolios, although it could be applied to other securities and assets.


## Intro

Sharpe ratio measures the performance of an investment such as a security or portfolio compared to a risk-free asset, after adjusting for its risk. Investors prefer portfolios with a higher Sharpe ratio, as it indicates that either higher returns or lower volatility.

## Stocks used
In this project, a portfolio containing four stocks were used : Apple, Google, Tesla and Nio.

## Obtaining data
Stock data was obtained using yahoo finance API, by importing the yfinance package.

```python
import yfinance

# obtaining stock data of Amazon from 10-09-2019 to 09-10-2019
df = yfinance.download('AMZN', start='2019-09-10', end='2019-10-09')

```

## Method

Define functions to generate mean daily returns and a covariance matrix for our stocks
Define function to randomly weight proportions of each stock in a portfolio and calculate the portfolio's risk-adjusted return (Sharpe ratio) and variance over a specified period of time
Use Monte-Carlo method to find weighting of stocks to maximize Sharpe ratio and minimize volatility


## Plot the portfolios, green star for max Sharpe, red for min Sharpe
![Unknown](https://github.com/zkaiW/StockPortfolioSharpeRatio/assets/76109881/567cb6ab-6b8a-4ac3-9dd2-08feb45e020c)
