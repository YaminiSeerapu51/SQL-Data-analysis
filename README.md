# SQL-Data-analysis
Zepto vs Blinkit: SQL Business Analysis 🧠📊

This project analyzes and compares two Indian delivery giants — Zepto and Blinkit — using SQL.
A total of 12 business questions are answered through modular SQL views, raw queries, and PowerPoint visuals.

# 📁 Project Structure
- views_script.sql → All views created to answer business questions
- raw_queries.sql → Raw SQL queries without using views
- Readme.md file

# 📊 Dataset Overview
3 tables were created manually and cleaned using Excel:

Table Name	Description
customers	Customer name, age, gender, email, city, state
products	Product name, brand (Zepto/Blinkit), category, price
orders	Date, time, total bill, quantity, product & customer IDs

# Key Business Questions Answered
1. Who are the top 5 customers by spend?
2. Which age group + brand generates the highest revenue?
3. What are the most ordered product categories by brand?
4. Age group-wise revenue split (young vs senior)
Top 3 selling products in each brand
Product categories exclusive to Zepto
Year-wise revenue comparison between brands
Top 3 cities by orders
Bottom 3 states by revenue
Month & Year-wise revenue trend
Weekend sales by brand
Customers with > 2 orders per brand
Total repeat orders (brand-wise)

# Technologies Used
- Excel – Data cleaning, quantity column generation
- MySQL – Joins, Aggregations, Window Functions, Views
- PowerPoint – Final insight presentation (13-slide deck)
- Power BI – For dashboard-level visualization

# Key SQL concepts Applied
- JOIN (Inner joins between 3 tables)
- GROUP BY, ORDER BY, HAVING
- CASE WHEN for segmenting age groups
- RANK() & WINDOW FUNCTIONS
- VIEWS for reusable business logic

# Usage
1. Import .csv files (customers, products, orders) into MySQL
2. Run views_script.sql to create all views
3. Run any query or SELECT * FROM view_name to analyze
4. Open the .pptx file to view business-level insights

# Future Scope






