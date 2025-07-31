# K-Nearest Neighbors (KNN) Trading Strategy for SPY

## Overview
This project implements a K-Nearest Neighbors (KNN) algorithm to develop a trading strategy for the SPDR S&P 500 ETF Trust (SPY). The strategy aims to predict buy/sell signals based on historical price data, achieving a Sharpe ratio of 1.24, indicating favorable risk-adjusted returns.

## Key Features
- **Data Preparation**: Fetches SPY historical data (2014-2024) using `yfinance` and derives predictor variables (`Open-Close`, `High-Low`).
- **Model Training**: Uses KNN (`k=20`) to classify trading signals (buy: +1, sell: -1) with a 49% test accuracy.
- **Strategy Performance**: Compares cumulative returns of the KNN strategy against passive SPY holding, visualized using `matplotlib`.
- **Risk-Adjusted Metrics**: Calculates the Sharpe ratio to evaluate excess returns per unit of volatility.

