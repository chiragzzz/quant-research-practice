# Quant Research Practice Projects

This repository contains hands-on projects for preparing quantitative research and data roles in finance/FinTech, using real-world datasets and SQL schemas.

---

## 📈 Apple Stock Data Analysis (Python + pandas)

- Cleaned and filtered Apple stock data
- Renamed columns and parsed dates
- Visualized closing prices using matplotlib
- Exported cleaned dataset to CSV

---

## 💾 SQL Practice: Stocks, Sectors, Funds & Investments

- Created realistic schemas for stock markets and asset management
- Ran JOINs, aggregations, and filters
- Used GROUP BY, HAVING, and subqueries
- Identified unallocated funds using LEFT JOIN
- Practiced identifying top performers by sector

---

### 🔍 Feature Engineering & Signal Logic

- Extended the Apple dataset with:
  - 7-Day Moving Average (MA_7)
  - 14-Day Volatility (rolling std)
  - Daily Returns (% change)
  - Simple Buy Signal: Close > MA_7
- Saved processed data as CSV: `apple_with_signals.csv`
- Saved visual chart of price + signal overlay: `apple_ma7_signal.png`

🖼 **Preview:**
![Apple Signal Plot](apple_ma7_signal.png)

---


## 📊  NIFTY vs BANKNIFTY Comparative Analysis (2023–2025)

- Downloaded historical daily prices for NIFTY and BANKNIFTY using yfinance
- Normalized both indices to a base value of 100 for fair comparison
- Visualized relative performance on a single plot
- Exported chart and data for further analysis

📘 [View Notebook](./Nifty_banknifty_compare.ipynb)

🖼 *Chart Preview:*
![NIFTY vs BANKNIFTY](nifty_banknifty_comparison.png)

📄 [Download Normalized Data (CSV)](./nifty_banknifty_normalized.csv)


---

## 📈 XAUUSD MA Strategy Backtest

Tests a simple moving average crossover on gold (XAUUSD).  
Buy when `Close > MA(7)`, hold for 5 days, exit.

- Trades: 49
- Avg Return/Trade: 0.14%
- Cumulative Return: +7.18%

![XAUUSD Strategy vs Buy and Hold](xauusd_strategy_vs_bh.png)

📘 [View Notebook](./xauusd_ma_backtest.ipynb)

## 🛠 Tools Used

- Python (pandas, matplotlib)
- SQL (SQLite via Jupyter)
- GitHub for version control

---

## 🔍 EURUSD Candlestick Pattern Detection

This project detects classic candlestick patterns using daily OHLC data for EURUSD (Jan–Jun 2025):

- 📍 Doji (indecision)
- 🔺 Bullish Engulfing (bullish reversal)
- 💎 Hammer (bullish reversal with long wick)

Each pattern is marked on an interactive Plotly candlestick chart.

📘 [View Notebook](./5.eurusd_candlestick_patterns.ipynb)  
📊 [View Interactive Chart](./5.eurusd_candlestick_patterns.html)  
📄 [View Labeled Dataset](./5.EURUSD_patterns_2025.csv)




## 🔗 Author

Chirag Puthran  
📧 chiragputhran31@gmail.com  
🌐 [LinkedIn](https://linkedin.com/in/chirag-puthran-01a316208)
