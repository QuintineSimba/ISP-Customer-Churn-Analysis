# ISP Churn Analysis - Microtech Networks

**3-year dashboard showing 2024 churn crisis (170% spike) and 2025 recovery (45% drop) with hidden infrastructure risk**

[📊 Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTBmMmY5NjUtYzc5OS00MDY4LThmYzEtMWQ5ZjNlZDY0NWVmIiwidCI6ImU0ZWVjNDM0LTk3N2MtNGI1Yy05MjJjLTc0ZTI0ZWVmNjVhMSJ9)

---

## The Problem

Microtech Networks needed to understand why customers were leaving. Was 2024 normal attrition or a crisis? Was 2025 really recovering?

---

## What I Built

**Interactive Power BI dashboard with year-over-year comparison (2023-2025)**

4 KPI cards tracking:
- Active Customers
- Churn Rate  
- Avg Satisfaction Score
- Total Revenue

Each KPI shows current value + year-over-year % change with color-coded arrows.

**Visuals:**
- Revenue by region (bar chart)
- Monthly trends (combo chart)
- Customer segments (donut charts)
- Service tickets by category (column chart)
- Year selector buttons + region/plan filters

---

## What The Data Showed

### 2024 = Crisis Year

| Metric | Value | vs 2023 |
|--------|-------|---------|
| Churn Rate | 17.46% | **+170.6%** 🔴 |
| Active Customers | 104 | -10.3% 🔴 |
| Outage Tickets | 63 | High |

2024 churn nearly tripled. Outages drove defections.

### 2025 = Recovery (With Warning)

| Metric | Value | vs 2024 |
|--------|-------|---------|
| Churn Rate | 9.44% | **-45.9%** 🟢 |
| Active Customers | 163 | +56.7% 🟢 |
| Revenue | Ksh460.9K | +37.2% 🟢 |
| **Outage Tickets** | **86** | **+37%** 🔴 |
| **Satisfaction** | **1.61** | **-26.4%** 🔴 |

Churn improved, customers grew, BUT outages increased and satisfaction dropped.

**Key Insight:** 2025 looks good on paper, but service quality is getting worse. Acquisition masked infrastructure problems.

---

## The Decision

**Fix infrastructure before scaling growth**

Despite 2025's strong numbers, I recommended:
1. Infrastructure audit in Ruiru-Gwakairo (82% of revenue)
2. Reduce 86 outages to <50 before aggressive expansion
3. Monitor new customer satisfaction (currently 1.61)
4. Don't repeat 2024's "growth masks churn" mistake

**Why:** Year-over-year data showed outages trending up (63→86), not down. This predicts future churn.

---

## Tools

- **Power BI:** Data modeling, dashboard, year-over-year comparisons
- **DAX:** KPI calculations with time intelligence (`SAMEPERIODLASTYEAR`)
- **Excel:** Data prep and validation

---

## How To Use

1. Download `Microtech.pbix`
2. Open in Power BI Desktop
3. Click year buttons (2023/2024/2025) to compare
4. Use slicers to filter by region/plan

**Or view the [live dashboard](https://app.powerbi.com/view?r=eyJrIjoiY2U3ZjFkMDItNjljOS00ZTQ5LThhMjktMzljNDVhMTAxZTJmIiwidCI6ImU0ZWVjNDM0LTk3N2MtNGI1Yy05MjJjLTc0ZTI0ZWVmNjVhMSJ9)**

---

## What This Shows

- Year-over-year analysis to spot patterns vs. snapshots
- Root cause analysis linking operations (outages) to business outcomes (churn)
- Leading indicators (satisfaction drop = future churn risk)
- Executive-ready dashboards (tell story in 30 seconds)

---

**Bottom Line:** 2024 was a crisis. 2025 recovered. But outages are increasing—fix that before 2026 repeats 2024.
