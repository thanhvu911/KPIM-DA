📊 Sales Planning Analysis Project
Date: August 2025
Tools: Power BI, Excel, DAX, SQL Server

📌 Overview
This project delivers a Sales Performance Dashboard in Power BI, designed to help executives and regional managers track sales KPIs against monthly plans across different stores, product groups, and regions.

The dashboard integrates actual sales data and monthly plan data from SQL Server using a Galaxy Schema design, enabling multi-dimensional analysis over time and across locations.

🎯 Objectives
Provide real-time KPI tracking for sales performance.

Compare actual vs. planned sales to monitor completion rates.

Identify year-over-year trends and growth opportunities.

Allow filtering by store, product group, region, and time period for granular insights.

🛠️ Data Sources & Architecture
SQL Server:

Sales Fact Table (actual transaction data)

Plan Fact Table (monthly sales targets)

Dimension Tables: Store, Product, Region, Time

Galaxy Schema:

Separate fact tables for Actual Sales and Sales Plans linked to shared dimensions.

Power Query: Used to clean, merge, and shape data from SQL Server.

📐 Key Features
Dynamic KPI Cards:

Total Sales, Plan Completion %, Year-over-Year Growth %

Visualizations:

Monthly trend lines for actual vs. plan

Store-level performance ranking

Product group & regional breakdowns

DAX Measures:

Plan Completion Rate = (Actual Sales / Planned Sales) * 100

YoY Growth %

Rolling 12-Month Trend calculations

📈 Insights Enabled
Identify top-performing stores and those at risk of missing targets.

Track seasonal and yearly growth patterns.

Monitor execution gaps at regional and product category levels.

Provide executives with data-driven decision-making tools.

