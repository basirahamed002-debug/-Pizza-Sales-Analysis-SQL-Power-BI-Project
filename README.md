# 🍕 Pizza Sales Analysis

A comprehensive end-to-end data analysis project using SQL for data querying and Power BI for interactive dashboarding. This project analyzes retail pizza sales data to identify key performance indicators (KPIs) like total revenue, average order value, and sales trends to drive business growth and operational efficiency

## 📌 Project Overview
This project provides a deep dive into the sales performance of a pizza store. By leveraging SQL for backend data extraction and Power BI for frontend visualization, I identified critical trends in customer behavior, popular pizza categories, and peak sales periods.

## 📊 Key Performance Indicators (KPIs)
Using SQL, I calculated the following essential business metrics:

### Total Revenue: The total price of all pizza orders.

### Average Order Value: The average amount spent per order.

### Total Pizzas Sold: The sum of the quantities of all pizzas sold.

### Total Orders: The total number of unique orders placed.

### Average Pizzas Per Order: The average number of pizzas sold per order.

## 🛠️ Tools Used
SQL (SQL Server): For data cleaning, transformation, and complex querying.
Power BI Desktop: For creating interactive dashboards and data modeling.
Excel/CSV: As the primary data source.

### 🔍 SQL Insights & Queries
The project involved writing optimized SQL queries to answer business questions, such as:
Daily & Monthly Trends: Analyzing order volume to identify peak hours and seasons.
Sales by Category: Understanding the percentage of sales contributed by different pizza categories (Classic, Veggie, etc.).
Size Analysis: Identifying which pizza sizes (Large, Medium, etc.) generate the most revenue.
Top & Bottom Performers: Identifying the best-selling and worst-selling pizzas by revenue, quantity, and total orders

(Example Query: Top 5 Pizzas by Revenue)
SELECT Top 5 pizza_name, SUM(total_price) AS Total_Revenue
FROM pizza_sales
GROUP BY pizza_name
ORDER BY Total_Revenue DESC;

### 📈 Power BI Dashboard Highlights
The dashboard provides an interactive experience with the following features:
Executive Summary: A high-level view of all KPIs.
Trend Charts: Visualizing daily and monthly sales patterns to optimize staffing.
Product Performance: A drill-down into pizza categories and sizes.
Interactive Filters: Ability to filter the entire dashboard by Pizza Category or Size
