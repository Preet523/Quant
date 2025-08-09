# Quant Strategy Projects
This repository showcases three progressively developed quantitative trading strategies. Each project applies a different approach — from momentum to mean reversion to a combined comparative model — with improvements in design, signal logic, and risk management throughout.

## Project Overview
### 1. Momentum Backtest

- First modular backtesting framework

- Implements momentum signals using SMA and volatility

- Basic signal confirmation

- Lays foundation for future improvements

### 2. Pairs Trading
- Mean Reversion Strategy

- Trades on the spread between two correlated assets

- Generates signals based on deviations from a rolling mean

- Adds confirmation lag to reduce false entries

- Enhances signal generation logic

### 3. Mean-Momentum Comparison
- Momentum vs. Mean Reversion

- Final and most advanced project

- Implements both strategies on the same dataset

- Adds tiered signal strength, partial position allocation

- Uses a drawdown threshold to manage risk

- More robust tracking of portfolio value and performance

## Skills Demonstrated
Strategy design & hypothesis testing

Signal generation with volatility & trend logic

Modular backtesting architecture

Risk controls (drawdown gating, partial allocation)

Pandas, NumPy, yfinance

## What They Show
These projects simulate realistic quant workflows — building, testing, and evaluating systematic strategies using historical data. They demonstrate core competencies in both programming and quantitative thinking, with an emphasis on iteration and improvement.

## Getting Started
pip install pandas yfinance matplotlib

Each notebook is self-contained. Run them top to bottom to reproduce results.
