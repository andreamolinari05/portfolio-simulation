# Quantitative Portfolio Risk Analysis

## Overview
This project implements a **risk-aware equity portfolio construction framework** using Monte Carlo simulations and downside risk metrics. The goal is to build a diversified portfolio that balances expected returns with volatility, correlation, and drawdown risk.

## Key Features
- Monte Carlo simulation using **Geometric Brownian Motion (GBM)**
- Correlated asset returns via **Cholesky decomposition**
- Portfolio allocation penalizing **correlation** and **downside risk**
- **Value at Risk (VaR)** analysis
- Benchmark comparison against **SPY ETF**

## Assets Included
- Nestlé (NESN.SW)
- Volkswagen (VOW3.DE)
- Coca-Cola (KO)
- Roche (ROG.SW)
- Johnson & Johnson (JNJ)

## How to Run
1. Open `portfolio_analysis.ipynb` in **Jupyter Notebook** or **Google Colab**
2. Install required packages:

pip install pandas numpy matplotlib yfinance scipy

3. Run all cells
