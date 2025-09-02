# Quant Strategy & Risk Projects
This repository showcases four progressively developed quantitative trading strategies and risk management projects. Each project applies a different approach — from momentum to mean reversion to comparative modeling and risk analysis — with improvements in design, signal logic, and portfolio risk controls throughout.

## Project Overview
### 1. Momentum Backtest

First modular backtesting framework

- Implements momentum signals using SMA and volatility

- Basic signal confirmation

- Lays foundation for future improvements

### 2. Pairs Trading
Mean Reversion Strategy

- Trades on the spread between two correlated assets

- Generates signals based on deviations from a rolling mean

- Adds confirmation lag to reduce false entries

- Enhances signal generation logic

### 3. Mean-Momentum Comparison
Momentum vs. Mean Reversion

- Final and most advanced project

- Implements both strategies on the same dataset

- Adds tiered signal strength, partial position allocation

- Uses a drawdown threshold to manage risk

- More robust tracking of portfolio value and performance

## 4. VaR & CVaR Risk Analysis
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

Pandas, NumPy, yfinance

## What They Show
These projects simulate realistic quant workflows — building, testing, and evaluating systematic strategies using historical data, then extending into formal risk analysis. They demonstrate core competencies in both programming and quantitative thinking, with an emphasis on iteration, improvement, and practical portfolio risk management.

## Getting Started
pip install pandas yfinance matplotlib

Each notebook is self-contained. Run them top to bottom to reproduce results.
