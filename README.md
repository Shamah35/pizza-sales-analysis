# Pizza Sales Analysis

## Overview

This project analyzes pizza sales data for 2015 using SQL and Power BI. It explores overall sales performance, order patterns, pizza category and size contributions, and the best and worst selling pizza varieties.

The Power BI report has two pages: **Home**, which summarizes sales and ordering trends, and **Best/Worst Sellers**, which compares pizza names by revenue, quantity sold, and number of orders.

## Key figures

The report displays:

- **Total revenue:** $817.86K
- **Average order value:** $38.31
- **Pizzas sold:** 49,574
- **Orders:** 21,350
- **Average pizzas per order:** 2.32

## Main findings

- **Friday has the most orders** in the daily trend, with Saturday also among the busiest days. This may help with staffing and preparation planning for the weekend.
- **July has the most orders** in the monthly trend, while October has the fewest. Comparing this pattern across years would help determine whether it reflects seasonality or a one-year fluctuation.
- **Classic pizzas contribute the largest category share** in the report, at about 26.9% of sales.
- **Large pizzas contribute the largest size share**, at about 45.9% of sales.
- **The Thai Chicken Pizza leads revenue** in the best-seller comparison.
- **The Classic Deluxe Pizza leads quantity sold and total orders** among the best sellers.
- **The Brie Carre Pizza appears among the weakest performers** by revenue, quantity, and orders. This could be a candidate for a menu or promotion review, but the report alone does not explain why it sells less.

## Analysis approach

SQL queries calculate revenue, average order value, pizza quantity, order count, average pizzas per order, daily and monthly order trends, sales shares, and top and bottom pizzas by revenue, quantity, and orders. Power BI presents those measures as summary cards, charts, and date/category filters.

## Files

- `Pizza Sales Querries.sql` — SQL analysis queries
- `pizza_sales.csv` — source sales data
- `pizza_sales_excel_file.xlsx` — Excel version of the data
- `PIZZA SALES SQL QUERIES.docx` — written SQL query document
- `pizza_sales_report.pbix` — add the Power BI report file, if available
- `screenshots/` — add report screenshots for readers who do not have Power BI

## Notes and limitations

The figures and patterns describe the attached 2015 dataset. They show associations in the sales data; they do not establish why a particular day, month, category, size, or pizza performs differently.

Before publishing, check the SQL file’s labels and calculations: its query labeled “Total Pizzas Sold by Pizza Category” groups by pizza name and sums revenue, and its pizza-size percentage query filters to the first quarter. Make sure those match the intended analysis and the full-year dashboard before presenting them as final results.
