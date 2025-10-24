# Portfolio Value at Risk (VaR) with Monte Carlo Simulation

This project provides a Jupyter Notebook (`.ipynb`) script to calculate the Value at Risk (VaR) for a financial portfolio. It uses the **Monte Carlo simulation method** to estimate the maximum potential loss over a specific time horizon, given a certain confidence level.

The script fetches historical market data from **yfinance**, calculates the portfolio's key statistics (expected return, volatility, and covariance matrix), and then runs thousands of simulations to model the portfolio's potential future performance.

## Features

* Fetches historical price data for any list of stock/ETF tickers.
* Calculates daily logarithmic returns.
* Determines the portfolio's expected return and standard deviation based on a covariance matrix (accounting for diversification).
* Runs 10,000 Monte Carlo simulations to generate a distribution of potential outcomes.
* Calculates the final VaR (e.g., at 95% confidence for a 5-day period).
* Visualizes the distribution of gains/losses with the VaR cutoff point highlighted in a histogram.
