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

## 🛠 Tools Used

- Python (pandas, matplotlib)
- SQL (SQLite via Jupyter)
- GitHub for version control

---

## 🔗 Author

Chirag Puthran  
📧 chiragputhran31@gmail.com  
🌐 [LinkedIn](https://linkedin.com/in/chirag-puthran-01a316208)
