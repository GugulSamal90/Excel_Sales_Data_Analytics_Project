# Excel_Sales_Data_Analytics_Project

# ABC Executive Summary & Profitability Dashboard

## Project Overview

An interactive **Sales Analytics and Profitability Dashboard built using Microsoft Excel** to monitor business performance across revenue, gross profit, gross margin, cost of goods sold (COGS), order volume, product categories, sales channels, and European markets.

The project transforms transaction-level sales data into an executive reporting dashboard using Excel formulas, PivotTables, KPI cards, charts, and interactive slicers.

## Business Problem

Analyzing raw sales transactions makes it difficult for business stakeholders to quickly understand profitability, track monthly performance, compare countries, and identify the contribution of different sales channels.

This project addresses the problem by consolidating key business metrics into an interactive dashboard that supports sales performance monitoring, financial reporting, and data-driven decision-making.

## Key Features

- **Executive KPI Dashboard:** Displays Total Revenue, Total Gross Profit, Gross Profit Margin, Total Units Sold, Total Orders, and COGS.
- **Monthly Sales Analysis:** Visualizes monthly revenue and gross profit trends to compare performance over time.
- **Country-Level Analysis:** Compares revenue across countries to identify leading markets.
- **Sales Channel Analysis:** Evaluates revenue contribution from Corporate, Marketplace, Online Store, and Retail Partners.
- **Regional Performance Analysis:** Compares revenue distribution across Central, Northern, Southern, and Western Europe.
- **Geographic Visualization:** Presents country-wise revenue using a map chart.
- **Interactive Filtering:** Uses slicers for Product Category, Country, and Quarter to explore different business segments.
- **PivotTable Reporting:** Aggregates sales metrics by business dimensions to support dashboard visualizations.

## Dataset

The workbook contains **2,707 sales records and 20 columns**, organized into an Excel Table named `SalesDataTable`.

Key fields include:

- **Order Information:** ID, Order Date, Year, Quarter, Month No, Month
- **Business Dimensions:** Region, Country, Sales Channel, Customer Type
- **Product Information:** Product Category, Product
- **Sales Measures:** Units Sold, Unit Price, Discount %
- **Financial Measures:** Unit Cost, Revenue, COGS, Gross Profit, Gross Margin %

## Data Calculations

The workbook uses Excel formulas to derive time-based fields and financial metrics:

- **Year:** Extracted from Order Date using `YEAR()`.
- **Quarter:** Derived from the order month using `MONTH()` and `ROUNDUP()`.
- **Month and Month Number:** Calculated using `TEXT()` and `MONTH()` for monthly reporting.
- **Revenue:** Units Sold × Unit Price × (1 − Discount %).
- **COGS:** Units Sold × Unit Cost.
- **Gross Profit:** Revenue − COGS.
- **Gross Margin %:** Gross Profit ÷ Revenue, with `IFERROR()` used to handle division errors.

## Tools & Technical Skills

- Microsoft Excel
- Excel Tables and Structured References
- Excel Formulas and Calculated Columns
- PivotTables and Data Aggregation
- Interactive Slicers and Dashboard Filtering
- KPI Development and Financial Reporting
- Data Visualization and Chart Design
- Sales Trend and Profitability Analysis
- Business Intelligence and Executive Reporting

## Workbook Structure

| Worksheet | Purpose |
|---|---|
| `Data` | Transaction-level sales data and calculated fields |
| `Pivot Tables` | Aggregated sales summaries supporting KPIs and charts |
| `Dashboard` | Executive KPIs, charts, map visualization, and interactive slicers |

## How to Use

1. Open the Excel workbook in Microsoft Excel.
2. Navigate to the **Dashboard** worksheet.
3. Use the Product Category, Country, and Quarter slicers to filter the analysis.
4. Review the KPI cards and charts to compare sales trends, profitability, regional performance, and channel contribution.
5. Explore the Pivot Tables and Data worksheets to inspect the supporting summaries and source records.

## Project Outcome

Developed an interactive Excel dashboard that consolidates sales and profitability metrics into a single reporting interface, enabling users to explore performance by time period, geography, product category, and sales channel.

## Resume Summary

**ABC Executive Summary & Profitability Dashboard | Microsoft Excel**

- Developed an interactive Excel dashboard to track revenue, gross profit, gross margin, COGS, units sold, and order volume across 2,707 sales records.
- Applied Excel formulas, structured tables, and PivotTables to aggregate and analyze sales performance across multiple business dimensions.
- Designed KPI cards, trend charts, channel and regional comparisons, country-level analysis, and interactive slicers for executive reporting and business insights.

