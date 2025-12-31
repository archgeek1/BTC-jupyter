## Overview
The `BTC-sar-rsi-ema.ipynb` notebook downloads and processes daily Bitcoin (BTC/USD) candle data. It calculates basic statistics such as daily returns, annualized return and volatility, Sharpe ratio, maximum drawdown, win rate, and a 95% Value at Risk (VaR). The notebook also computes a 30-day rolling volatility series and provides simple visualizations of returns and volatility.

In addition to the summary statistics, we plot technical indicators used for trading analysis: EMA, Parabolic Stop and Reverse (PSAR), and RSI. It uses `mplfinance` to plot candlesticks with EMA and PSAR overlays and a separate RSI subplot. These plots and metrics make the notebook useful as a custom alternative to commercial tools for exploratory analysis and for generating publication-ready charts.

`BTC-sar-rsi-ema.ipynb` can be viewed directly in Github

## Prerequisites
- Familiarity with jupyterlab
- Install dependencies using either `conda` or `pip` and run jupyter

### Option 1: Conda (recommended)
Create the environment from `environment.yml`:

```bash
conda env create -f environment.yml
conda activate btc-jupyter

# Start the server
jupyter lab
```
### Option 2: pip
If you prefer `pip`, create and activate a virtual environment first, then install dependencies:

```bash
pip install pandas numpy matplotlib mplfinance ta tabulate jupyterlab

# Start the sever
jupyter lab
```