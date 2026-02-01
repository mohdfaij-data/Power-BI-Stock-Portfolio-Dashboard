# 📊 Stock Portfolio Performance Dashboard | Power BI

![Dashboard Preview](https://github.com/mohdfaij-data/Power-BI-Stock-Portfolio-Dashboard/blob/main/Stock%20Portfolio%20Dashboard.png)

---

## 🚀 Project Overview

This project is an interactive **Stock Portfolio Performance Dashboard** developed in **Microsoft Power BI** to monitor and evaluate equity portfolio performance using key financial KPIs and sector-level analytics.

It provides a single-page, decision-focused view of portfolio health by combining:

✅ Investment Exposure  
✅ Current Valuation  
✅ Net Profitability  
✅ Sector-wise Return Contribution  

---

## 📌 Project Snapshot

- 🏦 **Domain:** Finance Analytics  
- 🛠 **Tool Used:** Microsoft Power BI  
- 📊 **KPIs Tracked:** Investment, Current Value, Profit, Return %  
- 🎯 **Interactivity:** Sector slicers & drill-down analysis  
- 📈 **Purpose:** Portfolio monitoring & performance reporting  

---

## ❓ Business Questions Answered

This dashboard helps answer real investor-focused questions such as:

- 💰 How much capital is invested across stocks?
- 📈 What is the current market value of the portfolio?
- ✅ Am I net profitable and what is my return percentage?
- 🏢 Which holdings dominate portfolio exposure?
- 🧩 Which sectors are driving overall returns?

Instead of manual spreadsheet tracking, insights are surfaced instantly through dynamic visuals.

---

## 📊 Dashboard Insights & Features

### ✅ Portfolio KPI Summary
- **Total Investment (Capital Deployed)**
- **Current Portfolio Value**
- **Net Profit / Loss**
- **Portfolio Return (%)**

---

### 📌 Stock Allocation (Exposure Analysis)
A stock-wise investment distribution highlights where capital is concentrated and how diversified the holdings are.

---

### 🏭 Sector Allocation & Diversification
Sector breakdown helps assess portfolio risk exposure across industries.

---

### 📉 Sector-wise Return Contribution
Returns are evaluated at the sector level to identify:

✅ Outperforming sectors  
✅ Underperforming sectors  
✅ Return contribution by allocation  

---

### 📈 Portfolio Growth Trend
A trend chart provides time-based monitoring of portfolio performance movement.

Interactive slicers allow sector-level drilldowns for focused exploration.

---

## 🧾 Dataset Information

The dataset contains standard portfolio attributes:

- Stock Name & Sector Classification  
- Buy Price vs Current Price  
- Quantity Held  
- Invested Amount  
- Current Market Value  
- Profit / Loss  
- Return Percentage  

*(Dataset is prepared for educational and portfolio demonstration purposes.)*

---

## 🧠 DAX Measures (KPI Engine)

```DAX
Total Investment =
SUM(Portfolio[Investment Amount])

Current Value =
SUM(Portfolio[Current Value])

Net Profit =
[Current Value] - [Total Investment]

Portfolio Return % =
DIVIDE([Net Profit], [Total Investment], 0)

---

📂 Repository Contents
📌 Dashboard.pbix — Power BI report file
🖼 dashboard.png — Dashboard preview image
📊 dataset.xlsx — Portfolio dataset
📘 README.md — Project documentation


🔮 Future Enhancements
Planned improvements for upcoming versions:
⭐ Top Gainers vs Top Losers Table
📅 Monthly Portfolio Performance Tracking
🔄 Automated Live Stock Price Integration
⚠️ Risk Metrics (Volatility, Sharpe Ratio)


👤 Author
Mohd Faij
Aspiring Data Analyst | Power BI & Finance Analytics
📌 GitHub: https://github.com/mohdfaij-data
📌 LinkedIn: (https://www.linkedin.com/in/mohd-faij-a364953a4)


🛡 Ownership
© 2026 Mohd Faij. All rights reserved.
This project is created for portfolio and educational demonstration purposes.
If you use this work, please provide appropriate credit.

⭐ If you found this project valuable, feel free to star the repository!```
