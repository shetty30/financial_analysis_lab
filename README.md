# 🏦 Bank Profitability Dashboard  

Analyze **branch-wise** and **region-wise** performance of a bank using  
**SQL + Pandas + Matplotlib** — find which branches are profit engines and which ones bleed due to NPAs.  

---

## 💡 Overview  

Every quarter, banks report numbers for each branch: income, expenses, NPAs, deposits, and loans.  
This project turns those figures into insights:  

- ✅ Profit per branch and region  
- 💰 Profit margin % and NPA ratio %  
- 🔄 Loan-to-deposit ratio %  
- 📉 Profit trend by quarter  

---

## 📈 Outputs  

### 🟢 Profit by Branch  
Compare profitability across all branches.  

### 🟠 Profit Margin vs NPA Ratio  
Shows which branches balance efficiency and credit risk.  

### 🔵 Average Profit Margin by Region  
Breakdown of profitability across regions.  

### 🟣 Profit Trend by Quarter  
Total profit growth over FY25 — quarter by quarter.  

---

## 🧮 Key Metrics  

| Metric | Formula |
|---------|----------|
| **Profit (₹ cr)** | Total Income − Total Expense |
| **Profit Margin %** | Profit / Income × 100 |
| **NPA Ratio %** | NPA / Loan Book × 100 |
| **Loan–Deposit Ratio %** | Loan Book / Deposits × 100 |

---

## 🚀 Future Ideas  

- Risk-adjusted profit metric → `Profit ÷ NPA Ratio`  
- Add quarterly comparisons for every branch  
- Create a Streamlit version for interactive dashboards
