# Portfolio Optimisation and Risk Analytics

A Python project demonstrating portfolio optimisation techniques and risk analysis for financial data analytics.

## Overview

This project fetches historical stock price data, performs mean-variance optimisation to find optimal portfolio weights, and calculates key risk metrics used in the finance industry.

## Features

- **Data Collection**: Fetch historical prices from Yahoo Finance
- **Return Analysis**: Calculate returns, volatility, and correlations
- **Portfolio Optimisation**: Mean-variance optimisation with efficient frontier
- **Risk Metrics**: Value at Risk (VaR) and Conditional VaR (CVaR/TVaR)
- **Monte Carlo Simulation**: Forward-looking portfolio projections

## Technologies

- Python 3.14
- pandas & numpy for data manipulation
- yfinance for market data
- matplotlib & seaborn for visualisation
- scipy for optimisation

## Project Structure

```
portfolio-optimisation/
├── README.md
├── requirements.txt
├── notebooks/
│   └── 01_data_exploration.ipynb
├── src/
│   └── portfolio.py
└── outputs/
    └── (generated plots and results)
```

## Getting Started

1. Install dependencies:
   ```
   pip3 install -r requirements.txt
   ```

2. Open the notebooks in VS Code or Jupyter Lab

3. Run the cells sequentially to see the analysis

## Author

Amba - Mathematics and Actuarial Science, University of Leicester
