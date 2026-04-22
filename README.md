# NexaCommerce Global – FP&A Dashboard
### Power BI | DAX | Financial Modelling | Scenario Analysis

---

## Overview

NexaCommerce Global is a **senior-level FP&A dashboard** built in Power BI, simulating the financial intelligence layer of a fictional mid-size e-commerce company (FY2025). The project covers end-to-end financial planning and analysis — from revenue drivers to EBITDA, from customer cohorts to aging — designed to mirror the reporting demands of a real multi-entity finance function.

The dashboard is structured across **6 analytical pages**, each purpose-built for a different stakeholder decision:

| Page | Purpose |
|---|---|
| FP&A Model Summary | Executive KPI overview, budget vs. actual, variance flags |
| Sales Analysis | Revenue breakdown by product, region, and channel |
| Customer Analysis | Cohort analysis, CLV segmentation, acquisition trends |
| Profitability Analysis | Gross margin, contribution margin, EBITDA drill-down |
| Customer Aging Report | Receivables aging, overdue analysis, collection risk |
| Scenario / What-If Analysis | Revenue-to-EBITDA bridge with DAX-driven sensitivity sliders |

---

## Dashboard Preview

### 📊 FP&A Model Summary
Executive-level KPI overview with budget vs. actual performance and variance flags for senior leadership.

<img width="1143" height="611" alt="FP&A Model Summary" src="https://github.com/user-attachments/assets/cd89b46a-d417-47e6-976c-87f53b9bfa38" />

---

### 📈 Sales Analysis
Revenue breakdown by product line, region, and sales channel — with trend analysis across FY2025.

<img width="1157" height="652" alt="Sales Analysis" src="https://github.com/user-attachments/assets/82fa7e2b-e2fe-4e39-8a58-07c37cf1a463" />

---

### 👥 Customer Intelligence
Cohort analysis, customer lifetime value (CLV) segmentation, and acquisition trend tracking across 50 customers.

<img width="1120" height="635" alt="Customer Intelligence" src="https://github.com/user-attachments/assets/eadef873-3eb5-472c-93d1-cc19044248f7" />

---

### 💰 Profitability Analysis
Gross margin, contribution margin, and EBITDA drill-down — fully dynamic with slicers by segment, region, and product.

<img width="1148" height="647" alt="Profitability Analysis" src="https://github.com/user-attachments/assets/8f548ee5-d145-48ba-9fe6-d0b667317e93" />

---

### 🗓️ Customer Aging Report
Receivables aging schedule (0–30, 31–60, 61–90, 90+ days) with conditional formatting to surface high-risk overdue balances.

<img width="1153" height="650" alt="Customer Aging Report" src="https://github.com/user-attachments/assets/0c0b8b0d-1001-44e1-80db-99d7262ef122" />

---

### 🔮 Scenario / What-If Analysis
The standout page. Adjust revenue growth, cost ratios, and pricing assumptions via sliders — the Revenue-to-EBITDA bridge recalculates in real time using pure DAX.

<img width="1161" height="653" alt="Scenario Analysis" src="https://github.com/user-attachments/assets/5393b4ee-caf2-4600-bdb1-806dbf9413cd" />

---

## Key Features

### Revenue-to-EBITDA Bridge
A waterfall chart tracing the journey from gross revenue to EBITDA — accounting for COGS, gross profit, operating expenses, and EBITDA margin — with full DAX-driven dynamic recalculation as scenario inputs change.

### What-If / Scenario Modelling
Users can adjust key business levers using sliders — revenue growth rate, cost ratios, pricing assumptions — and see the downstream EBITDA impact recalculate in real time. Built entirely with DAX `SELECTEDVALUE`, `SWITCH`, and disconnected parameter tables (no Power Query dependency).

### Cohort & CLV Analysis
Customers are segmented by acquisition cohort and lifetime value tier. The analysis identifies which cohorts deliver the highest long-term revenue and where churn risk is concentrated — directly informing commercial strategy.

### Customer Aging Report
A receivables aging schedule (0–30, 31–60, 61–90, 90+ days) built using DAX date logic, with conditional formatting to surface high-risk overdue balances. Reflects real AR management processes.

### Variance Analysis
Budget vs. actual comparisons across revenue, cost, and margin lines — with conditional colour formatting to flag favourable (green) and adverse (red) variances automatically.

---

## Technical Stack

| Area | Details |
|---|---|
| **Tool** | Microsoft Power BI Desktop |
| **Data Modelling** | Star schema – Fact Sales + Dim Customer, Dim Product, Dim Date, Dim Region |
| **DAX** | 40+ measures including dynamic scenario logic, cohort calculations, aging buckets, YTD/MTD, variance % |
| **Data** | Fictional FY2025 dataset – 50 customers, 12 months, multi-product, multi-region |
| **Design** | Deep navy palette, teal accents, conditional variance formatting, consistent KPI card layout |

---

## Dataset Design

The dataset was purpose-built to reflect realistic FP&A complexity:

- **50 customers** across segments (Enterprise, Mid-Market, SMB)
- **Cohort fields** to enable retention and CLV analysis
- **Receivables data** with aging logic calibrated to realistic overdue patterns
- **EBITDA margin structure** aligned to SaaS/e-commerce benchmarks
- Revenue, COGS, OpEx, and headcount cost lines — enabling full P&L construction

---

## Why This Project

Most Power BI portfolios stop at sales charts and bar graphs. This project goes further:

- It models the **full FP&A cycle** — planning, reporting, variance analysis, and forward-looking scenario modelling
- The **Scenario page** is the differentiator: dynamic EBITDA sensitivity built in pure DAX, not Excel
- The **Aging Report** reflects real-world credit control workflows, not just cosmetic dashboards
- The **cohort and CLV layer** shows commercial finance thinking, not just operational reporting

This is the kind of analysis that Finance Directors and CFOs actually use to make decisions.

---

## About the Author

**Jamil Ur Rehman** | Finance & BI Analyst | Dubai, UAE

ACCA · FMVA · BIDA · MSc Economics  
6+ years across FP&A, financial modelling, M&A due diligence, and Power BI development in multi-entity environments.

[LinkedIn](https://www.linkedin.com/in/jamil-ur-rehman-acca/) | [jamil.akhunzada@gmail.com](mailto:jamil.akhunzada@gmail.com)
