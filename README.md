# Retail Sales Performance Dashboard

## Overview

This project is an interactive Power BI dashboard built using the Sample Superstore dataset. It provides insights into sales performance, profit trends, regional performance, and product analysis.

---

## Dashboard Features

- KPI Cards
  - Total Sales
  - Total Profit
  - Total Orders
  - Profit Margin

- Monthly Sales Trend
- Sales by Category
- Profit by Region
- Sales by Segment
- Top Products Table
- Interactive Filters (Region, Category, Order Date)

---

## Tools Used

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

---

## Dataset

Sample Superstore Dataset

---

## Dashboard Preview

> Add a screenshot of your dashboard inside the **Screenshots** folder and replace the image below.

![Dashboard](Screenshots/Dashboard.png)

---

## DAX Measures Used

```DAX
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Total Orders = DISTINCTCOUNT(Orders[Order ID])

Total Quantity = SUM(Orders[Quantity])

Profit Margin % = DIVIDE([Total Profit],[Total Sales],0)
```

---

## Project Highlights

- Cleaned and transformed sales data using Power Query.
- Created DAX measures for business KPIs.
- Designed an interactive dashboard with charts and slicers.
- Analyzed monthly sales trends and regional profit.
- Built a reusable dashboard for business reporting.

---

## Skills Demonstrated

- Data Cleaning
- Data Visualization
- Business Intelligence
- DAX
- Power Query
- Dashboard Design
- Data Analysis

---

## Author

Harshini
