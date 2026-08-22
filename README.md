# Global Superstore — Advanced Data Analysis & BI Dashboard

**AnalystLab Africa — Data Analytics Internship Programme**
**Week 3: Advanced Data Analysis, KPI Development & Business Intelligence Dashboard**

An interactive Power BI dashboard and supporting analysis built on the Global Superstore dataset (2011–2014), investigating where a fast-growing, multi-market retailer is genuinely profitable — and where volume is masking weak or negative margins.

---

## Overview

This project builds on the Week 2 exploratory analysis of the Global Superstore dataset. Week 3 goes deeper: KPI development, DAX-driven measures, discount and profitability analysis, and a four-page interactive dashboard designed for a business decision-maker rather than an analyst.

**Headline numbers:** $12.64M in sales, $1.47M in profit (11.61% margin), 25,035 orders, 1,590 customers, across 7 markets and 147 countries, 2011–2014.

## Business Problem

Global Superstore operates across markets with very different cost structures, discount practices and shipping realities. Revenue has grown 90% over four years, but growth in sales does not automatically translate into growth in profit. This project identifies exactly where that gap comes from — and what to do about it.

## Dataset

- **Source:** Global Superstore (Orders), single fact table
- **Grain:** One row per order line
- **Period:** January 2011 – December 2014
- **Scope:** 51,290 order lines · 3 categories · 17 sub-categories · 3,788 products · 1,590 customers · 7 markets · 147 countries

## Tools Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Data model, DAX measures, interactive dashboard |
| Power Query | Data cleaning and shaping |
| DAX | Calculated measures (Total Sales, Profit Margin, etc.) |
| Excel / Google Sheets | Supporting checks |
| GitHub | Version control and submission |



## Dashboard Pages

1. **Overview** — 6 headline KPIs, sales & profit trend, sales by market, profit by category
2. **Profitability** — profit by category/sub-category, sales vs. profit scatter, full sub-category breakdown table
3. **Discount Impact** — sales & profit by discount band, profit margin by discount band, discount vs. profit scatter
4. **Products & Regions** — top 10 / bottom 10 products, profit by region, market performance table

All pages share synchronized slicers (Year, Market, Category, Region/Segment as applicable).

## Key Insights

1. **Discounting above ~20% is structurally unprofitable** — margin falls from +25.3% at 0% discount to -51.3% above 30%.
2. **Tables is the only sub-category losing money in aggregate** — 67% of its products are individually unprofitable, at double the average discount rate.
3. **Furniture converts sales to profit far worse than other categories** — 6.9% margin vs. ~14% for Technology and Office Supplies.
4. **A small set of countries drive disproportionate losses** — Turkey and Nigeria alone account for -$179K.
5. **Demand is strongly seasonal** — November–December sales run roughly 3x February's, identically across all four years.

Full evidence, methodology and recommendations are in `Business_Insights_and_Recommendations_Report.docx`.

## DAX Measures

7 core measures (Total Sales, Total Profit, Total Orders, Total Customers, Profit Margin, Average Sales, Average Discount) plus 2 recommended time-intelligence measures (Sales Growth %, Profit Growth %). Full formulas and descriptions in `DAX_Measures_Documentation.docx`.

## How to Open

1. Open `dashboard.pbix` in Power BI Desktop (2023 or later recommended).
2. All data is embedded — no external data source connection required.
3. Use the slicers on each page to filter by year, market, category or region.



---


