## Overview
The `BTC-sar-rsi-ema.ipynb` notebook downloads and processes daily Bitcoin (BTC/USD) candle data. It calculates basic statistics such as daily returns, annualized return and volatility, Sharpe ratio, maximum drawdown, win rate, and a 95% Value at Risk (VaR). The notebook also computes a 30-day rolling volatility series and provides simple visualizations of returns and volatility.

In addition to the summary statistics, we plot technical indicators used for trading analysis: EMA, Parabolic Stop and Reverse (PSAR), and RSI. It uses `mplfinance` to plot candlesticks with EMA and PSAR overlays and a separate RSI subplot. These plots and metrics make the notebook useful as a custom alternative to commercial tools for exploratory analysis and for generating publication-ready charts.

`BTC-sar-rsi-ema.ipynb` can be viewed directly in Github

## Prerequisites
Install the following Python packages:
```bash
pip install pandas matplotlib mplfinance ta numpy
```