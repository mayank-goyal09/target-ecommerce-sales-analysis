# 🛒 Target E-Commerce Sales Analysis | [View Full Report PDF](e-commerce%20(target).pdf)

## Overview

Every purchase reveals a preference. Every customer tells a story. Every transaction captures a moment when someone decided your platform was worth their trust and money. When you understand these decisions at scale, you transform raw e-commerce data into strategic intelligence that shapes inventory planning, marketing campaigns, and revenue growth.

This project explores Target's e-commerce sales data through the combined power of Python and SQL. Rather than just tracking sales numbers, I focused on understanding the business dynamics that drive those numbers. Who are our most valuable customers? Which products and sellers generate the highest revenue? How do payment preferences affect purchasing behavior? When do customers return for repeat purchases? These questions matter because they translate directly into profitability, customer retention, and sustainable business growth.

## Why Python and SQL Together?

This analysis leverages both Python and SQL to maximize insights:

### Python's Role
* **Data pipeline automation** – Seamlessly load CSV files (customers, orders, sales, products, delivery, payments) into MySQL database
* **Data transformation** – Clean column names, handle missing values, and map pandas data types to SQL data types
* **Database management** – Automate table creation and data insertion with error handling
* **Scalability** – Process multiple tables efficiently with reusable functions

### SQL's Power  
* **Complex query execution** – Join multiple tables to uncover relationships between customers, orders, products, and sellers
* **Aggregation at scale** – Calculate revenue metrics, growth rates, and customer behavior patterns across millions of transactions
* **Time series analysis** – Track trends over months and years with cumulative calculations and moving averages
* **Advanced analytics** – Compute retention rates, year over year growth, and customer lifetime value

## Business Questions Explored

This analysis addresses strategic questions across three complexity levels:

### Basic Insights (Foundational Understanding)
1. **Geographic reach** – Where are customers located across cities and states?
2. **Transaction volume** – How many orders were placed in 2017?
3. **Category performance** – What is the total sales per product category?
4. **Payment behavior** – What percentage of orders use installment payments?
5. **State distribution** – How many customers come from each state?

### Intermediate Analysis (Pattern Recognition)  
1. **Monthly trends** – How do order volumes change month by month in 2018?
2. **City level behavior** – What is the average number of products per order by customer city?
3. **Revenue contribution** – Which product categories drive the most revenue percentage?
4. **Price correlation** – How does product price relate to purchase frequency?
5. **Seller rankings** – Who are the top revenue generating sellers?

### Advanced Metrics (Strategic Intelligence)
1. **Moving averages** – What are the order value trends for individual customers over time?
2. **Cumulative growth** – How do sales accumulate month by month each year?
3. **Year over year growth** – What is the annual growth rate of total sales?
4. **Customer retention** – What percentage of customers make repeat purchases?
5. **Top spenders** – Who are the top 3 customers by spending in each year?

## Technical Implementation

### Data Pipeline (Python)
The `csv_to_sql.py` script demonstrates professional data engineering:

* **Automated loading** of 6 CSV files into MySQL database
* **Dynamic type mapping** from pandas dtypes to SQL data types (INT, FLOAT, BOOLEAN, DATETIME, TEXT)
* **Null value handling** to ensure data integrity
* **Column name sanitization** for SQL compatibility  
* **Transaction management** with commit and rollback capabilities
* **Error handling** throughout the pipeline

### Query Structure (SQL)
The analysis progresses through 15 carefully crafted queries:

* **Basic queries** establish baseline metrics and distributions
* **Intermediate queries** reveal patterns through grouping and aggregation
* **Advanced queries** compute sophisticated metrics like moving averages, cumulative sums, and retention rates

Each query serves a specific business purpose, moving from descriptive statistics to predictive insights.

## Key Insights Uncovered

Through systematic Python and SQL exploration, this analysis reveals:

* **Revenue drivers** – The specific product categories and sellers generating the highest returns
* **Customer geography** – Where demand concentrates and which markets show growth potential
* **Purchase patterns** – How customers behave across order frequency, product quantity, and payment methods
* **Temporal trends** – When demand peaks throughout the year and how growth accelerates
* **Retention metrics** – Which customers return and what their lifetime value represents
* **Seller performance** – Who consistently delivers revenue and deserves strategic partnership focus

## Strategic Business Value

For an e-commerce platform, these insights translate into concrete actions:

### Operational Decisions
* **Inventory optimization** – Stock products and categories that drive revenue
* **Geographic expansion** – Target cities and states showing high customer concentration
* **Payment flexibility** – Offer installment options based on customer preference data
* **Seller partnerships** – Strengthen relationships with top revenue generating sellers

### Strategic Planning  
* **Customer retention programs** – Design campaigns targeting repeat purchase behavior
* **Pricing strategy** – Adjust prices based on correlation with purchase frequency
* **Growth forecasting** – Project future revenue using year over year growth rates
* **Market segmentation** – Tailor offerings to different customer value segments

### For Data Professionals
This project demonstrates:

* **End to end data pipeline** – From CSV files to actionable SQL queries
* **Python automation** – Building reusable data loading scripts
* **SQL proficiency** – Complex joins, window functions, aggregations, and time series analysis
* **Business thinking** – Translating technical queries into strategic recommendations
* **Multi tool integration** – Leveraging Python and SQL strengths together

## Technical Skills Demonstrated

### Python Capabilities
* Pandas for data manipulation and transformation
* MySQL connector for database operations
* Dynamic SQL query generation
* Error handling and transaction management
* File system operations and automation

### SQL Expertise  
* Multi table joins across 6 related tables
* Aggregate functions (SUM, COUNT, AVG, MIN, MAX)
* GROUP BY operations for categorical analysis
* Window functions for moving averages and rankings
* Date and time functions for temporal analysis
* Subqueries and CTEs for complex calculations
* Correlation analysis and statistical metrics

## Project Structure

This repository contains:

* **csv_to_sql.py** – Python script for automated data loading from CSV to MySQL
* **Questions.txt** – 15 business questions across Basic, Intermediate, and Advanced levels
* **e-commerce (target).pdf** – Complete analysis report with query results and insights
* **README.md** – This comprehensive project documentation

## The Data Journey

1. **Extract** – Source data from CSV files (customers, orders, sales, products, delivery, payments)
2. **Transform** – Clean, validate, and prepare data using Python
3. **Load** – Insert transformed data into MySQL database with proper schema
4. **Analyze** – Execute SQL queries to answer strategic business questions
5. **Insight** – Translate query results into actionable business recommendations

---

*This project demonstrates how Python and SQL work together to transform e-commerce transaction records into strategic business intelligence. Every query serves a purpose. Every insight drives a decision. Every analysis brings data closer to action.*
