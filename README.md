# Revenue Operations Conversion Analysis
### Pipeline Conversion Efficiency & Sales  Optimization

---

## Business Problem

A sales organization had strong pipeline volume but was generating below-benchmark revenue. The gap between pipeline size and actual revenue pointed to a conversion efficiency problem — but the specific causes were hidden inside the data.

The goal: identify exactly where and why conversion was breaking down from, and build a reporting infrastructure that makes revenue performance visible in real time.

---

## Context

**Domain:** Revenue Operations / Sales Operations  
**Tools:** Microsoft Excel (Power Query, Power Pivot, DAX), Excel Dashboard  
**Data Sources:** SQL databases, CSV files, PDF reports  
**Scope:** Full pipeline conversion analysis (March 2025-March 2026, with focus on Q4 2025 - Q1 2026) with dashboard delivery  
**Relevance to Payments/Fintech:** Directly mirrors merchant acquisition analytics, onboarding conversion tracking, and revenue operations functions within fintech platforms

---

## Approach

### Data Infrastructure Build

**Step 1 - Data Ingestion (Power Query)**
- Imported and transformed data from multiple sources: SQL databases, CSV files, PDF reports
- Cleaned and standardized inconsistent data formats
- Built automated refresh pipeline eliminating manual data handling

**Step 2 - Data Modeling (Power Pivot)**
- Built Sales Funnel relational data model
- Established relationships between leads, opportunities, pipeline stages, and rep performance tables
- Enabled multi-dimensional analysis across time, region, rep, and deal stage

**Step 3 - Metric Calculation (DAX)**
Key metrics calculated:
```
Win Rate = DIVIDE([Closed Won], [Total Opportunities])
Discount Percentage = [Price] - [Discount Price] / [Price]
Regional Performance Index = DIVIDE([Region Win Rate], [Benchmark Win Rate])
```

**Step 4 - Dashboard Delivery (Excel)**
Built Sales Performance Tracker Dashboard with:
- Executive summary KPIs
- Regional performance heatmap
- Rep-level conversion breakdown
- Pipeline stage funnel visualization
- Trend analysis over time

---

## Key Metrics (Dashboard Output)

| Metric | Value |
|--------|-------|
| Total Pipeline Revenue | ₦27.5M |
| Total Sales | 463 |
| Win Rate | 46.3% |
| Discount % | 9.03% |


---

## Key Findings

**Finding 1 — Regional Performance Gaps of 15-20 Percentage Points**
Significant conversion rate variance across regions — highest-performing regions (50.31%)converting at 10-15 percentage points above lowest-performing regions (36.51%). Not a market problem — a process and capability problem.

**Finding 2 — Rep-Level Conversion Bottlenecks**
Bottom-quartile reps were disproportionately dragging overall conversion rates. The gap between top and bottom performers (~59% Points) was masking underlying pipeline health.

**Finding 3 — Pipeline Velocity Was Strong — Conversion Was Weak**
Leads were entering the pipeline at a healthy rate. The failure was happening at the qualification and closing stages — indicating a skills and process gap rather than a demand gap.

**Finding 4 — No Consistent Qualification Criteria**
Reps were progressing deals at different standards — inflating pipeline with low-probability opportunities and creating false revenue confidence.

---

## Recommendations

### 1. Targeted Coaching Programs
Focus coaching resources on bottom-quartile reps — specifically at the qualification and closing stages where conversion was breaking down.

**Business Impact:** Individual performance improvement of 25%-140% modeled across rep cohorts.

### 2. Standardized Qualification Criteria
Implement consistent deal qualification standards across all regions — ensuring pipeline only contains opportunities that meet minimum probability thresholds.

**Business Impact:** More accurate revenue forecasting. Cleaner pipeline. Better resource allocation.

### 3. Regional Performance Accountability
Establish regional benchmarks and regular performance review cadence — making regional gaps visible to leadership in real time through the dashboard.

**Business Impact:** Faster identification and correction of underperforming regions.

---

## Business Impact

- Win rate improvement: **46% → 78%**
- Bottom-quartile conversion improvement: **36% → 90%+**
- Individual rep performance improvement modeled at **25% to 140%**
- Company revenue increase potential: **25-50%**

---

## Fintech/Payments Relevance

This project directly mirrors key functions in fintech Revenue Operations:

| Sales Ops Concept | Payments/Fintech Equivalent |
|-------------------|----------------------------|
| Lead conversion rate | Merchant onboarding conversion rate |
| Pipeline by region | Merchant acquisition by geographic corridor |
| Rep performance analysis | Agent/field team performance analysis |
| Deal qualification | Merchant risk and eligibility screening |
| Revenue forecasting | Transaction volume and MDR revenue forecasting |

The analytical frameworks, DAX metrics, and dashboard design are directly transferable to merchant analytics, agent network performance, and revenue forecasting functions in a payments operations environment.

---

## Skills Demonstrated

`Power Query` `Power Pivot` `DAX`  `Data Modeling` `Sales Funnel Analysis` `Conversion Rate Optimization` `Revenue Operations` `Dashboard Design` `Multi-Source Data Integration`

---

## Files in This Folder

- `README.md` - This file
- [dashboard_screenshot](Dashboard/Dashboard_Image.png) - Sales Performance Tracker Dashboard
- [Data-Sources](Data_Sources)