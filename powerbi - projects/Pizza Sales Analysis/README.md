# Pizza Sales Performance Dashboard

## Project Overview
This Power BI project provides a comprehensive analysis of pizza sales data to identify key performance indicators (KPIs), customer trends, and operational insights. The dashboard is designed to help stakeholders monitor business performance and optimize sales strategies.

## Key Features & Insights
The report is structured into multiple pages, each focusing on a specific business aspect:

- **Executive Summary:** High-level overview of total revenue, average order value, and total pizzas sold.
- **Sales Trends:** Analysis of daily and monthly sales patterns to identify peak hours and seasonal demand.
- **Product Performance:** Breakdown of sales by pizza category and size to evaluate product contribution.
- **Customer Preferences:** Identification of top-selling and low-performing pizzas to support menu optimization decisions.

## Technical Stack
- **Power BI Desktop:** Used for data modeling, DAX development, and report visualization.
- **DAX (Data Analysis Expressions):** Custom measures created for business metrics, including:
  - Total Revenue: `SUM(Sales[Total_Price])`
  - Average Order Value: `[Total Revenue] / [Total Orders]`
  - Total Pizzas Sold: `SUM(Sales[Quantity])`
- **Data Modeling:** Implemented a star schema connecting the sales fact table with dimension tables for date, pizza category, and size.

## Visualizations Included
- **KPI Cards:** Revenue, total orders, and quantity sold
- **Bar / Column Charts:** Sales comparison across categories and sizes
- **Line Charts:** Sales trends over time
- **Donut / Pie Charts:** Distribution of sales by category
