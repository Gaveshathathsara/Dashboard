# Case Study: Retail Sales Dashboard

## The Problem
A small retail shop had sales data scattered across receipts and notebooks, with no easy way to see which products were selling well, which months were strongest, or where customers were coming from.

## The Approach
I structured the raw sales data into a clean, formula-driven table, then built 5 PivotTables to answer specific business questions. Each was paired with the chart type best suited to what it needed to show — a line chart for the monthly trend, a pie chart for category share of revenue, bar charts for rankings, and column charts for location and category comparisons.

## Key Decisions
- Used formulas (not hardcoded numbers) throughout, so the dashboard recalculates automatically as new sales data is added
- Added a secondary axis to the monthly trend chart, since revenue (in the hundreds of thousands) and units sold (in the hundreds) would otherwise flatten one line against the other
- Sorted the best-sellers table by units sold, since that's the standard definition of "best-selling," while keeping revenue visible alongside it
- Consolidated all 5 charts onto a single Dashboard sheet for an at-a-glance view

## The Result
The dashboard lets the shop owner instantly see which products to restock, which months are strongest or weakest, and where their customers are located — all without digging through raw data.

## Tools Used
Microsoft Excel — PivotTables, PivotCharts, formulas, dual-axis charts

![Dashboard Screenshot](dashborad.png)
