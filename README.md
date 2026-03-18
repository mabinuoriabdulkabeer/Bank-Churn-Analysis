# Bank Churn Analysis (Interactive Dashboard · Power BI)

## Project Objective
A retail bank wanted to understand why customers were leaving and identify which segments were most at risk. This project analyses 10,000 customer records to uncover the key drivers of a 20.37% churn rate — significantly above the industry benchmark of 15% — and translate those findings into actionable retention strategies.

---

## Questions (KPI)
The dashboard was built to answer the following business questions:

1. **Scale** — How many customers churned, and what is the financial impact?
2. **Segments** — Which customer groups are churning at the highest rates?
3. **Geography** — Are certain countries disproportionately affected?
4. **Behaviour** — Does account activity level predict churn?
5. **Demographics** — How do age, gender, and credit profile influence attrition?
6. **Tenure** — At what point in the customer lifecycle does churn peak?

---

## Process
1. **Data exploration** — Reviewed 10,000 customer records across 12 attributes including balance, geography, age group, credit score, activity status, and churn outcome
2. **Metric development** — Built DAX measures for churn rate, retention rate, average balance by segment, deposits at risk, and segment-level churn rates
3. **Iterative dashboard design** — Designed an interactive Power BI dashboard featuring ranked bar charts for segment comparison, benchmark-referenced KPI cards, and a dedicated action signal section translating findings into prioritised retention interventions
4. **Insight generation** — Identified four high-priority segments with specific recommended interventions

---

## Dashboard
![Dashboard](https://github.com/mabinuoriabdulkabeer/Bank-Churn-Analysis/blob/main/Bank%20Churn%20Dashboard.png)

---

## Key Findings
- **$185.6M in deposits at risk** — churned customers held an average balance of $91.1K, $18.4K higher than retained customers
- **Age 51–65** churn rate of 52.96% — more than 1 in 2 customers in this group leaves
- **Germany** churns at 32.44%, twice the rate of France (16.15%) and Spain (16.67%)
- **Non-active members** churn at 26.85% vs 14.27% for active members — a 12.58pp gap and the strongest leading indicator of attrition
- **Low credit score** customers churn at 32.97%, 65% above medium and high tiers

---

## Recommendations
- Launch priority retention outreach for 51–65 customers with balances above $100K
- Investigate Germany independently — exit surveys and local competitor pricing review required
- Trigger re-engagement campaigns for customers with no account activity in 90+ days
- Evaluate a lower-fee product tier for low credit score customers to reduce affordability-driven attrition
- Add churn rate trend monitoring once time-series data becomes available

---

## Tools Used
| Tool | Purpose |
|------|---------|
| Power BI | Dashboard development and visualisation |
| DAX | Measure creation and calculated columns |

---

*Dataset: 10,000 customer records · Domain: Retail Banking · Period: Static snapshot (no date dimension)*
