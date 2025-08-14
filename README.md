# 💰 Bank Loan Report – Summary Dashboard

![Bank Loan Dashboard](assets/bank_loan_dashboard.png)

## 📌 Overview
The **Bank Loan Report Dashboard** provides a detailed view of loan application performance, funding amounts, repayments, and loan quality metrics.  
It enables financial institutions to monitor portfolio health, identify risk areas, and track performance changes over time.

---

## 📊 Key Metrics
| Metric | Value | MoM Change |
|--------|-------|------------|
| **Total Loan Applications** | 1.8K | -3.0% |
| **Total Funded Amount** | $24.1M | -1.4% |
| **Total Amount Received** | $23.8M | +0.9% |
| **Average Interest Rate** | 13.03% | +2.2% |
| **Average DTI** | 11.14% | — |

---

## 📂 Dashboard Features
- **KPI Summary Cards** for at-a-glance performance metrics.
- **Good vs Bad Loan Segmentation** with funded and received amounts.
- **Loan Status Breakdown** (Fully Paid, Current, Charged Off).
- **Interactive Filters** by:
  - Loan Purpose (e.g., car, credit card, small business, medical)
  - Loan Grade (A–G)
  - Borrower State (all U.S. states)
- **MoM (Month-over-Month) Tracking** to measure trends.

---

## 📈 Loan Quality Insights
- **Good Loans**:
  - Applications: **1.3K** (74.4% of total)
  - Funded Amount: **$17.5M**
  - Amount Received: **$20.5M**
- **Bad Loans**:
  - Applications: **0.5K** (25.6% of total)
  - Funded Amount: **$6.7M**
  - Amount Received: **$3.4M**

---

## 📊 Loan Status Summary
| Status       | Applications | Amount Funded | Amount Received |
|--------------|--------------|---------------|-----------------|
| Fully Paid   | —            | $411.6M       | $411.6M         |
| Current      | 1,098        | $24.2M        | $24.2M          |
| Charged Off  | 5,333        | $37.3M        | $37.3M          |

---

## 🛠 Technical Details
- **Tool Used**: Microsoft Excel (PivotTables, Charts, Slicers)
- **Data Source**: Bank loan transaction dataset
- **Visual Components**:
  - KPI cards
  - Donut charts for loan distribution
  - Horizontal bar charts for loan status
  - Interactive slicers for dynamic filtering

---

## 📁 Repository Structure

📦 Bank_Loan_Report

┣ 📜 BankLoan_Dashboard.xlsx # Excel dashboard

┣ 📜 README.md # Documentation

┗ 📂 assets

┗ 📜 bank_loan_dashboard.png

---
##📌 Future Enhancements

Live connection to a bank loan database for automated updates.

Time-series charts for year-over-year trends.

Power BI / Tableau version for online accessibility.
