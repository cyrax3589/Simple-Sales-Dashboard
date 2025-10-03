# Superstore Sales Dashboard (Power BI)

This project showcases an interactive Power BI dashboard built using Superstore sales data. It provides key business insights such as sales performance across categories, regions, and time.

---

## Objectives

- Analyze total sales by category, region, and month.
- Visualize trends over time (monthly sales).
- Identify top-selling products.
- Enable interactivity with slicers (region, category, date).
- Generate insights for business decisions.

---

## Dashboard Overview

| Visual | Description |
|--------|-------------|
| KPI Card | Displays total sales across all orders (₹2.26M). |
| Bar Chart | Shows sales distribution across regions (West leads). |
| Donut Chart | Breaks down sales by product category. |
| Line Chart | Monthly sales trend from Jan 2015 to Sep 2017. |
| Table | Top-selling products by total sales. |
| Slicers | Interact by Region, Category, and Order Date range. |

---

## Key Insights
1. The West region contributed the highest sales, totaling ₹0.71M.
2. Furniture is the best-performing category (₹827.46K, ~37% of total).
3. October 2015 and December 2016 were peak sales months (₹82K and ₹75K respectively).
4. Top product: “1.7 Cubic Foot Compact 'Cube' Office Refrigerators” sold ₹1.47L alone.
5. Noticeable dips occurred mid-2016 — possibly due to seasonality or external factors.

---

## Tools Used

- Power BI Desktop
- Power Query for data cleaning and transformation
- DAX for calculated columns and measures

---

## Data Cleaning Summary


- Converted Order Date and Ship Date to proper Date format using locale (en-GB).
- Casted Sales as number and other columns to appropriate data types.
- Created a MonthYear column using DAX:  
  ```DAX
  MonthYear = FORMAT('Superstore_Sales'[Order Date], "MMM YYYY")


## Key insights
    1. The West region led in total sales, generating ₹0.71M, followed closely by the East with ₹0.67M.

    2. Among product categories, Furniture performed best with ₹827.46K in sales (36.59%), followed by Office Supplies and Technology.

    3. October 2015 and December 2016 were the strongest sales months, reaching ₹82K and ₹75K respectively.

    4. Top product by revenue: "1.7 Cubic Foot Compact 'Cube' Office Refrigerators" with ₹1.47L in total sales.

    5. Sales peaked during Q4 of each year, indicating seasonal demand trends worth capitalizing on in future campaigns.

## Visual

