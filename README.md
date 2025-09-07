# Quant Strategy & Risk Projects
Aspiring quantitative researcher/analyst
- Name: Preet Gill
- Degree: Computer Science at Loughborough University (2nd Year)

This repository showcases four progressively developed quantitative trading strategies and risk management projects. Each project applies a different approach — from momentum to mean reversion to comparative modeling and risk analysis — with improvements in design, signal logic, and portfolio risk controls throughout.

The projects are listed **in chronological order**; the most technically advanced are projects #3 & #4.

Each project title is clickable.


## Project Overview
### 1. [Momentum Backtest](https://github.com/Preet523/Quant/blob/main/Notebooks/momentum.ipynb)

First modular backtesting framework

- Implements momentum signals using SMA and volatility

- Basic signal confirmation

- Lays foundation for future improvements

### 2. [Pairs Trading](https://github.com/Preet523/Quant/blob/main/Notebooks/pairs-trading.ipynb)
Mean Reversion Strategy

- Trades on the spread between two correlated assets

- Generates signals based on deviations from a rolling mean

- Adds confirmation lag to reduce false entries

- Enhances signal generation logic

### 3. [Mean-Momentum Comparison](https://github.com/Preet523/Quant/blob/main/Notebooks/mean-momentum.ipynb)
Momentum vs. Mean Reversion

- Final and most advanced project

- Implements both strategies on the same dataset

- Adds tiered signal strength, partial position allocation

- Uses a drawdown threshold to manage risk

- More robust tracking of portfolio value and performance

## 4. [VaR & CVaR Risk Analysis](https://github.com/Preet523/Quant/blob/main/Notebooks/VaR.ipynb)
Risk Estimation & Backtesting

- Calculates Value at Risk (VaR) using historical, parametric, and Monte Carlo methods

- Extends to Conditional VaR (CVaR) to measure expected loss beyond VaR

- Backtests VaR to compare predicted vs. actual exceedances

- Visualizes return distributions and risk thresholds

- Demonstrates portfolio-level risk evaluation alongside strategy design

## Skills Demonstrated
Strategy design & hypothesis testing

Signal generation with volatility & trend logic

Modular backtesting architecture

Risk controls (drawdown gating, partial allocation)

Risk estimation (VaR, CVaR) & backtesting

Data visualisation & interpretation

Pandas, NumPy, yfinance, matplotlib

## What They Show
These projects simulate realistic quant workflows — building, testing, and evaluating systematic strategies using historical data, then extending into formal risk analysis. They demonstrate core competencies in both programming and quantitative thinking, with an emphasis on iteration, improvement, and practical portfolio risk management.

## Getting Started
pip install pandas yfinance matplotlib

Each notebook is self-contained. Run them from top to bottom to reproduce results.
