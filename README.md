# Sales Market Pre/Post Invoice Insights - SQL Project

## Overview
This project focuses on optimizing the analysis of sales data by incorporating both pre-invoice and post-invoice deductions. It provides a detailed calculation of net sales and includes dynamic reporting for various markets and customers. The SQL queries and stored procedures developed in this project enable financial teams to generate more accurate reports and make data-driven decisions efficiently.

## Files
- **Sales_Market_Pre_Post_Invoice_Insights_SQL.sql**  
   Contains SQL queries and database views for the analysis of sales data, incorporating pre- and post-invoice deductions, and calculating net sales.

## Key Features
1. **Pre-Invoice Discount Report:**
   - SQL queries to include pre-invoice deductions in detailed sales reports.
   - Optimized performance by including fiscal year directly in the `fact_sales_monthly` table.

2. **Database Views Creation:**
   - Created views for **pre-invoice discounts**, **post-invoice discounts**, and **net sales**, enabling efficient and reusable query structures.
   - The final view, `net_sales`, consolidates pre- and post-invoice deductions for accurate financial reporting.

3. **Stored Procedures:**
   - `get_top_n_markets_by_net_sales`: Retrieves the top N markets by net sales for a given fiscal year.
   - `get_top_n_customers_by_net_sales`: Retrieves the top N customers by net sales for a given market and fiscal year.
   - `get_top_n_products_per_division_by_qty_sold`: Retrieves the top N products by division based on total quantity sold for a given fiscal year.

4. **Ranking Algorithms:**
   - Implemented `row_number()`, `rank()`, and `dense_rank()` functions to rank products, markets, and customers based on sales performance.

## Conclusion
This project enhances sales data analysis by providing an efficient, dynamic, and accurate method to calculate and report on net sales, incorporating both pre- and post-invoice 
deductions. It improves financial reporting accuracy, supports decision-making, and offers insights into top-performing markets, customers, and products.
