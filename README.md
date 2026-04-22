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

## Dashboard Preview

> Screenshots and full walkthrough available on request.  
> Contact: [jamil.akhunzada@gmail.com](mailto:jamil.akhunzada@gmail.com) | [LinkedIn](https://www.linkedin.com/in/jamil-ur-rehman-acca/)

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




