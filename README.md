# Stock Market Risk Analysis: AAPL vs SPY

## Overview
This project analyzes and compares the risk and return characteristics of Apple (AAPL) and the S&P 500 ETF (SPY) using historical market data from 2019 onwards.
The objective is to evaluate risk-adjusted performance and understand how single-stock exposure compares to a diversified market ETF.

---

## Data Source
- Yahoo Finance (via yfinance API)
- Daily adjusted closing prices

---

## Metrics Implemented
- Daily returns
- Cumulative growth of $1 investment
- Annualized return
- Annualized volatility
- Sharpe ratio (risk-free rate = 0)
- Rolling 1-year volatility
- Correlation analysis
- Maximum drawdown

---

## Key Findings
- AAPL delivered higher annualized return and higher Sharpe ratio compared to SPY.
- AAPL exhibited significantly higher volatility (31%) vs SPY (19.6%).
- Maximum drawdowns were comparable (~ -33%).
- Correlation (~0.77) indicates strong co-movement with the broader market.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- yfinance

---

## Future Improvements
- Include additional assets for diversification comparison
- Implement rolling Sharpe ratio
- Add simple trading strategy backtesting
- Introduce Monte Carlo portfolio simulations
