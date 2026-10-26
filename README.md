# Andes Retail Commercial Performance 2024–2025

**Author:** Rodrigo Garza García  
**Role:** Public & International Affairs | Business Analysis & Data Analytics  
**Portfolio:** [GitHub Profile](https://github.com/rogarzag)

Commercial performance analysis and interactive Tableau dashboard for **Andes Retail Group**, covering revenue, margin, orders, customer segments, product categories, geography, and seasonality across 2024–2025.

## 📊 Interactive Dashboard

Explore the full interactive dashboard on Tableau Public:

[View Dashboard on Tableau Public](https://public.tableau.com/app/profile/rodrigo.garza.garc.a/viz/Andes_Retail_Commercial_Performance_2024_2025/Dashboard-Overview)

## 🎯 Business Objective

This project analyzes how commercial performance evolved between 2024 and 2025 and explores the geographic, seasonal, customer, and product patterns associated with those changes.

Two complementary dashboards were developed:

- **Dashboard - Overview:** executive view of KPIs, monthly trends, customer segments, and product categories.
- **Dashboard - Detail:** deeper analysis of geographic, seasonal, and product performance, including order-level detail.

## Decision Brief

**Decision supported:** identify which components of the 2025 commercial decline should be investigated before changing category, campaign, or inventory priorities.

Revenue fell 6.8% while orders fell 3.9% and Average Order Value declined from 1,122.90 to 1,089.23 (approximately 3.0%). Both fewer orders and a lower average order value contributed to the revenue decrease; the dashboard does not establish their underlying causes.

| Evidence from the analysis | Business implication | Recommended action | How to evaluate the next step |
|---|---|---|---|
| Revenue, margin amount, orders, and average order value declined in 2025. | Recovery requires examining both transaction volume and value. A lower margin amount alone does not show that the margin rate deteriorated. | Break down the changes by category, country, and segment; review pricing, discounts, and product mix where data are available. | Track orders, average order value, revenue, and margin rate versus comparable periods. |
| Home moved from the lowest-revenue category in 2024 to the highest in 2025. | A change in rank may reflect Home's performance, declines elsewhere, or both. | Compare absolute category changes, order counts, average order value, and margin before shifting inventory or promotion budgets. | Monitor category revenue change, revenue share, margin rate, and orders. |
| Economy generated the lowest revenue and margin amount. | A smaller total does not establish lower customer value or efficiency. | Compare segment size, orders per customer, average order value, and margin rate before changing targeting. | Evaluate per-customer metrics and margin rate where the required data exist. |
| Summer revenue exceeded Winter revenue by more than three times; June–August were weaker months. | Calendar labels and geographic context need to be reconciled before seasonal planning. | Verify how Season is defined by country and compare equal periods before testing campaign timing or inventory adjustments. | Monitor revenue and orders by month and country, using a documented season definition. |

**Suggested priority:** investigate order volume and average order value first, then validate category changes and seasonal definitions. Proposed actions have not been implemented or evaluated for business impact.

## 📈 Dashboard - Overview

![Dashboard Overview](Overview.png)

### Main KPIs

| Metric | 2024 | 2025 | Change |
|---|---:|---:|---:|
| Revenue | 2,863,384 | 2,668,610 | **-6.8%** |
| Margin | 1,005,811.62 | 935,937.71 | **-6.9%** |
| Orders | 2,550 | 2,450 | **-3.9%** |
| Average Order Value | 1,122.90 | 1,089.23 | Decreased |

Across both years, Andes Retail Group generated **5.53M in revenue, 1.94M in margin, and 5,000 orders**.

## 🔎 Dashboard - Detail

![Dashboard Detail](Detail.png)

## 💡 Key Findings

- Revenue declined by approximately **6.8% in 2025**, accompanied by lower margin, order volume, and Average Order Value.
- **Home moved from the lowest-revenue category in 2024 to the highest-revenue category in 2025.**
- The **Economy** customer segment consistently generated the lowest revenue and margin.
- **Peru** generated the highest revenue among the countries analyzed.
- **Summer generated more than three times the revenue of Winter.**
- All product categories reached their highest revenue during Summer.
- Monthly performance was weaker between **June and August**, followed by a rebound toward year-end.

## Interpretation & Limitations

- Findings describe the available 2024–2025 data; they do not establish what caused the decline.
- Margin is the monetary difference between revenue and cost in the workbook. It should be distinguished from margin rate and net profit.
- Category rankings and segment totals should be interpreted alongside their absolute changes, customer counts, and transaction mix.
- The dataset's Season labels should be checked against country and month before using them for planning. Summer should not automatically be equated with June–August.
- Two years of observations are insufficient to establish a stable long-term seasonal forecast.
- Monetary values use the source dataset's units; currency denomination is not established in this README.
- Recommendations are proposed next steps, not measured improvements.

## 🛠 Tools

- Tableau Public
- Business Analysis
- Data Visualization
- KPI Analysis
- Dashboard Design
- SCQA Business Communication

## 📓 Analysis Notebook

The portfolio version of the project notebook is available in this repository:

[`andes_retail_commercial_performance_portfolio.ipynb`](andes_retail_commercial_performance_portfolio.ipynb)

## 🔗 Tableau Public

[Explore the interactive workbook](https://public.tableau.com/app/profile/rodrigo.garza.garc.a/viz/Andes_Retail_Commercial_Performance_2024_2025/Dashboard-Overview)
