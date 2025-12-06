# 📈 Global Portfolio Optimization using Modern Portfolio Theory (MPT)

This project implements a complete **Modern Portfolio Theory (MPT)** framework in Python.  
It analyzes **3 years of global index data**, selects the **Top 5 performing indices**, and computes:

- Minimum Variance Portfolio  
- Tangency (Maximum Sharpe) Portfolio  
- Efficient Frontier  
- Capital Market Line (CML)  
- Portfolio Allocation Breakdown (Doughnut Chart)

---

## 🔍 Project Overview

This model uses 3 years of historical data from several global indices, including:

- USA (S&P 500, NASDAQ 100)  
- Europe (FTSE, DAX, CAC, SMI)  
- Asia (Nikkei 225, Hang Seng, KOSPI, Shanghai Composite, CSI 300)  
- India (Nifty 50, Sensex)  
- Australia, Brazil, Canada  

The script automatically selects the **Top 5 performers** based on total percentage returns.

---

## 🧠 Techniques Used

- Log Return Calculation  
- Annualized Mean Returns  
- Covariance Matrix Estimation  
- Sharpe Ratio Maximization  
- Mean–Variance Optimization  
- Efficient Frontier Construction  
- Risk–Return Visualization  
- Donut Chart Allocation

**Tools:** Python, Pandas, NumPy, SciPy (SLSQP optimizer), yFinance, Matplotlib

---

## 📊 Results Summary

### **📌 Tangency Portfolio (Maximum Sharpe Portfolio)**

| Metric | Value |
|--------|-------|
| Expected Return | **26.1%** |
| Volatility | **15.9%** |
| Sharpe Ratio | **1.39** |

---

### **📌 Minimum Variance Portfolio**

| Metric | Value |
|--------|-------|
| Expected Return | **17.0%** |
| Volatility | **12.1%** |

---

### 🔎 Interpretation & Insights

- Tangency Portfolio provides **~118% higher return** than the Minimum Variance portfolio.  
- Volatility increases only **~31%**, confirming strong **risk-adjusted performance**.  
- Efficient Frontier shows optimal trade-offs between risk and return.  
- Allocation plot clearly visualizes weight distribution across global markets.

---

## 🖼️ Visual Output

### **Efficient Frontier Plot**
