# Maven Market – Topline Performance Dashboard

This Power BI project, *Topline Performance*, presents a comprehensive analysis of a fictional grocery chain’s performance. The dashboard delivers actionable insights by combining data from customers, products, stores, transactions, and returns in the year 1998.

## Project Overview

The goal of this project was to build an end-to-end business intelligence solution, starting from raw CSV files and resulting in a polished, interactive dashboard. Key metrics such as transactions, revenue, profit, returns, and profit margin are visualized to help stakeholders assess overall business health and performance across locations and product brands.

## Key Steps

- **Data Preparation**: Connected to multiple flat files using Power BI’s Query Editor. Applied transformations such as column merging, conditional logic, calculated fields, and data type formatting. Combined transaction data from multiple sources and ensured consistency across tables.

- **Data Modeling**: Structured the data using a star schema with clearly defined relationships. Lookup tables were connected to two central fact tables for transactions and returns. Proper cardinality and filter directions were enforced, and foreign keys were hidden for a cleaner report view.

- **DAX Calculations**: Created a robust set of measures and calculated columns to power the analysis, including revenue, cost, profit, return rate, YTD performance, 60-day rolling metrics, and month-over-month comparisons.

- **Dashboard Design**: Built an interactive report page with KPIs, maps, treemaps, column charts, and matrix visuals. Filters and slicers were used to enhance interactivity. Visuals were formatted for clarity and used conditional formatting, Top N filters, and bookmarks to highlight insights and support storytelling.

## Files Included

- `Jules Maven Market Power BI Report.pbix` – Power BI report file  
- `Maven Market Topline Performance Dashboard Jules B.pdf` – Static export of the dashboard layout

## Key Insights

The dashboard highlights:
- Top-performing product brands by transaction volume and profitability  
- Geographic breakdown of sales across cities and countries  
- Revenue trends and how they track against targets  
- Drill-down capabilities to explore regional and store-level performance
