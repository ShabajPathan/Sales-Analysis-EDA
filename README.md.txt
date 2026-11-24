# Superstore Sales Analysis

A beginner data analyst project on the Superstore orders dataset. It covers data cleaning, business KPIs, exploratory analysis, SQL queries, and a two-page Power BI dashboard.

## Objective

Understand where revenue and profit come from, and recommend simple actions a business can take.

## Dataset

- Source file: `sales.xlsx` (Orders sheet)
- About 10,000 order lines
- Columns used: Order Date, Customer, Segment, Region, State, Category, Sub-Category, Sales, Quantity, Discount, Profit

## Tools

- Python (Pandas, Matplotlib) in Google Colab
- SQLite for SQL analysis
- Power BI Desktop for the dashboard

## What was done

1. **Cleaning** — converted dates, created Year, Month, and Profit Margin %, removed nothing critical (no missing sales values).
2. **KPIs** — Total Sales, Total Profit, Profit Margin, Total Orders, Average Order Value (AOV).
3. **EDA** — monthly trend, category and sub-category, customer segment, region and state.
4. **SQL** — the same business questions in SQLite (KPIs, monthly, category, region, segment, top states, top sub-categories, yearly trend, discount impact, top customers).
5. **Power BI** — two pages:
   - **Overview** — KPI cards, monthly sales and profit, sales by region
   - **Product** — sales and profit by category, top sub-categories, sales by segment

## Key findings

- Total sales are about **$2.3M**, profit about **$286K**, profit margin about **12.5%**, orders about **5,000**, AOV about **$459**.
- Sales rise toward the end of the year (September–December).
- **West** is the strongest region.
- **Technology** is healthier on profit. **Furniture** has high sales but a weak profit bar.
- **Consumer** is about half of sales. Corporate and Home Office are smaller.
- **Phones** and **Chairs** are among the top sub-categories.

## Recommendations

- Review high discounts on low-margin furniture.
- Push technology products, where margin is better.
- Plan inventory for the peak months at the end of the year.
- Keep focus on the Consumer segment, and test offers for Corporate and Home Office.

## Dashboard

Screenshots:

- sales_bi_report_page-1
- sales_bi_report_page-2

Power BI file: `Superstore_Sales_Analysis.pbix`

## How to run the Python part

Open `EDA_and_Insights.ipynb` in Google Colab, upload `sales.xlsx`, and run the cells from top to bottom.