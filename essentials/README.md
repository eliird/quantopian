# Downloading data

```bash
pip install yfinance
```

## Notebooks
 
 - `data_download.ipynb` explains how to download data using yfinance
 - `bactest_mac.ipynb` explains how to backtest moving average crossover
 - `unrealized_pnl.ipynb` deals with how to look at pnl whil position is open
 - `evaluating_strategy.ipynb` metrics of how to evaluate a strategy.
 - `commissions.ipynb` incorporate commissions in backtest (needs install of TA-Lib)  


## Notes

### What makes a good strategy?

- Depends on:
    - Investment goals
    - Time Horizon
    - Risk appetite

- High Sharpe Ratio
    - Good measure but not perfect

- Small drawdowns
- Manageble risk
    - Be very careful with scaling positions
- Acceptable profit per trade in relation to trading costs
- Acceptable hold times
- Low beta
    - otherwisw just hold the benchmark

### What assets to trade?

- what assets classes should I trade?
- what backtesting periods should I use?
- How many parameters can I use?
- How about data quality?
- Where can I find strategy ideas?
- How much automation do I need to implement?
- what about execution?

# Sources

Ideas for strategy.

- [quantocracy](https://quantocracy.com/)
- [alpha_architect](https://alphaarchitect.com/blog/)
- [better_system_trader](https://bettersystemtrader.com/)