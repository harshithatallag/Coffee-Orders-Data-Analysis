# ☕ Coffee Orders Sales Dashboard (Excel)

## Overview
Interactive sales analytics dashboard built in Microsoft Excel. The workbook combines coffee orders with customer and product reference tables to report sales trends, product performance, geography, and customer value.

<img width="1251" height="710" alt="Image" src="https://github.com/user-attachments/assets/00c64c62-dc81-4c51-baa4-95887c53b3ab" />

## Business Questions Answered
1. How do total sales change over time
2. Which coffee types generate the most sales
3. Which countries contribute the most to total sales
4. Who are the top customers by sales
5. How do sales change when filtering by roast type, size, and loyalty status

## Dataset Summary
1. Time period: Jan 2, 2019 to Aug 10, 2022
2. Orders: 957 unique orders
3. Customers: 913 unique customers
4. Products: 48 unique products
5. Total sales: $45,134.26
6. Average order value: $47.16
7. Total quantity sold: 3,551

## What I Built
1. Prepared an analysis ready Orders table by combining order transactions with customer and product attributes from separate sheets
2. Calculated core KPIs for sales performance and customer ranking
3. Built an interactive Excel dashboard using pivot visuals and slicers for date, coffee type, roast type, size, country, and loyalty status

## Key Metrics Tracked
1. Total Sales
2. Total Orders
3. Total Quantity Sold
4. Average Order Value
5. Sales by Coffee Type
6. Sales by Country
7. Top Customers by Sales

## Insights From This Dataset
All figures below are calculated from the Orders table, and cross checked against pivot totals.
1. Sales are highly concentrated in the United States: $35,638.89 (79.0% of total)
2. Pack size 2.5 drives most revenue: $23,785.57 (52.7% of total)
3. Light roast leads revenue share: $17,354.46 (38.5% of total)
4. Coffee type contribution is relatively balanced, with Robusta lagging: $9,005.25 (20.0% of total)
5. Loyalty status does not increase basket size: average order value is $45.08 for Loyalty Yes vs $49.12 for Loyalty No
6. Revenue is not dependent on a few customers: Top 5 customers contribute $1,472.91 (3.3% of total)

## Files
1. coffeeOrdersProject.xlsx  
Final Excel workbook with dashboard and supporting sheets
2. coffeeOrdersData.xlsx  
Source dataset used for the project


## How to Review
1. Open coffeeOrdersProject.xlsx
2. Go to the Dashboard sheet
3. Use slicers to filter by date range, coffee type, roast type, size, country, and loyalty status
4. Review sales trend, country contribution, coffee type performance, and top customers

## Next Enhancements
1. Recreate the same analysis in SQL to automate joins, QA checks, and KPI calculations for larger datasets
2. Rebuild the dashboard in Power BI to improve refresh, sharing, and distribution
