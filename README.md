# 📊 Sales & Finance Analytics — AtliQ Hardware

A complete Excel-based analytics project covering sales performance and financial health for AtliQ Hardware across FY 2019–2021. Built on a star schema data model with Power Pivot, Power Query, and DAX.

---

## 📁 Project Objective

- Analyse customer-level and market-level sales performance across fiscal years
- Build structured P&L reports by fiscal year, month, and market to support financial decision-making

---

## 📋 Reports Overview

### 1. Customer Net Performance Report
Tracks net sales for each customer in India across FY 2019, 2020, and 2021, with YoY growth percentages.
- **Key Insight:** Overall India net sales grew from $30.8M (2019) to $161.3M (2021) — a **324% increase**
- **Top Performers:** AtliQ Exclusive (+392%), Electricalslytical (+431%), Girias (+419%)
- **Steady Large Accounts:** Amazon led absolute sales at $23M in 2021

---

### 2. Market Performance vs. Target Report
Compares actual 2021 net sales against set targets across 23 countries globally.
- **Key Insight:** Every market missed its 2021 target — total shortfall of **-$54.9M (-9.2%)**
- **Biggest Gaps:** USA (-$10.2M), India (-$9.6M), Canada (-$5.1M)
- **Closest to Target:** Japan (-4.1%), Portugal (-4.3%)

---

### 3. P&L Report by Fiscal Year
Summarises net sales, COGS, gross margin, and GM% across FY 2019–2021.
- **Key Insight:** Net sales tripled from $87.5M to $598.9M, but **GM% declined from 41.4% → 36.4%**
- **Takeaway:** Rapid revenue growth came at the cost of margin compression — COGS grew faster than revenue

---

### 4. P&L Report by Markets (GM% by Quarters)
Breaks down gross margin percentage by sub-division (ANZ, India, NE, ROA, SE) across all quarters for each fiscal year.
- **Key Insight:** India consistently held the **lowest GM%** (~32%), while ROA and SE maintained ~38–44%
- **Trend:** ANZ saw the sharpest GM% decline from 42.6% (2019) to 38.3% (2021)
- **Most Stable:** NE and SE sub-divisions showed the least quarterly volatility

---

### 5. P&L Report by Fiscal Months
Monthly breakdown of net sales, COGS, gross margin, and GM% across all 12 fiscal months for FY 2019–2021.
- **Key Insight:** Fiscal Q2 (Nov–Dec) consistently peaks — Dec 2021 hit **$78.1M** in net sales
- **YoY Growth:** 2021 vs 2020 monthly growth averaged ~161–165%, consistent across all months
- **Margin Stability:** GM% held steady within a narrow 36.2–36.7% band throughout FY 2021

---

## 🗃️ Data Model

Built using a proper **star schema** in Power Pivot with 7 connected tables:

| Table | Type |
|---|---|
| Fact_sales_monthly | Fact table |
| Dim_product | Dimension |
| Dim_customer | Dimension |
| Dim_market | Dimension |
| Dim_date | Dimension |
| NS_targets_2021 | Targets reference |

---

## 🛠️ Tools & Skills Used

| Tool | Purpose |
|---|---|
| Power Query | Data cleaning and transformation across 7 tables |
| Power Pivot | Star schema data modelling |
| DAX Measures | Custom KPIs — Net Sales, GM%, YoY growth |
| Pivot Tables | Dynamic report building |
| Conditional Formatting | Visual performance indicators |
| Excel Formulas | Supporting calculations |

---

## 🎯 Key Learnings

- Building a **star schema data model** instead of flat file analysis
- Writing **DAX measures** for time intelligence and YoY comparisons
- Handling **1M+ row datasets** efficiently without performance issues
- Translating raw sales data into **business-relevant insights**
- Understanding why **revenue growth alone doesn't guarantee profitability** improvement

---

## 📁 Project File

📊 [Download / View Full Excel Workbook](#)
