# SQL Sales Data Analytics Project

**An end-to-end SQL analytics project focused on exploring sales data, identifying business trends, analyzing customer and product performance, and generating actionable business insights using Microsoft SQL Server.**

---

## 📌 Project Overview

This project demonstrates the application of SQL for Exploratory Data Analysis (EDA) and Advanced Data Analytics using a sales database containing information from CRM and ERP source systems.

The objective is to transform raw sales data into meaningful business insights by exploring datasets, analyzing performance trends, identifying customer purchasing behavior, and evaluating product performance.

The project is divided into two major phases:

- **Exploratory Data Analysis (EDA):** Understanding the database structure, exploring dimensions and measures, and identifying patterns in the data.
- **Advanced Data Analytics:** Applying advanced SQL techniques to analyze trends, evaluate business performance, segment customers, and generate analytical reports.

The project concludes with two comprehensive reports: Customer Report and Product Report.

---

**SQL Concepts & Techniques:**

- Joins and Aggregate Functions
- Common Table Expressions (CTEs)
- Subqueries
- Window Functions
- CASE WHEN Statements
- Date and Time Functions
- Data Segmentation
- Ranking Functions
- NULL Handling and Type Casting

---

## 📊 Project Workflow

### Phase 1: Exploratory Data Analysis (EDA)

The first phase focuses on understanding the database and exploring the available data to identify patterns, relationships, and key business metrics.

| Analysis | Description |
|---|---|
| Database Exploration | Examining database objects, tables, and their structures. |
| Dimensions Exploration | Understanding categorical attributes such as customers, products, and categories. |
| Date Exploration | Identifying date ranges and understanding the time coverage of the dataset. |
| Measures Exploration | Exploring numerical metrics such as sales, quantity, and price. |
| Magnitude Analysis | Comparing business metrics across different dimensions. |
| Ranking Analysis | Identifying top-performing and lowest-performing products and customers. |

### Phase 2: Advanced Data Analytics

This phase focuses on extracting deeper insights from the data using advanced SQL techniques.

**1. Changes Over Time Analysis**

Analyzing how sales and other business metrics change over different time periods to identify trends and patterns.

**Techniques:** Date functions, aggregation, GROUP BY.

**2. Cumulative Analysis**

Calculating running totals and cumulative business metrics to understand how performance develops over time.

**Techniques:** Window Functions, SUM() OVER(), ORDER BY.

**3. Performance Analysis**

Evaluating business performance by comparing current metrics against historical or average performance to identify growth and declines.

**Techniques:** Window Functions, aggregate functions, CASE WHEN.

**4. Part-to-Whole Analysis**

Understanding the contribution of individual categories to overall business performance.

**Techniques:** Aggregate Functions, percentage calculations, subqueries.

**5. Data Segmentation**

Grouping customers and products into meaningful categories based on purchasing behavior, sales, and other business attributes.

**Techniques:** CASE WHEN, conditional logic, GROUP BY.

**6. Customer Report**

Developing a customer-level analytical report to evaluate purchasing behavior, customer value, and engagement.

Key metrics include:

- Total Orders
- Total Sales
- Total Quantity Purchased
- Total Unique Products Purchased
- Customer Lifespan
- Recency (Months Since Last Order)
- Average Order Value (AOV)
- Average Monthly Spend

**7. Product Report**

Developing a product-level analytical report to evaluate sales performance, product demand, and revenue contribution.

Key metrics include:

- Total Orders
- Total Sales
- Total Quantity Sold
- Total Unique Customers
- Product Lifespan
- Recency (Months Since Last Sale)
- Average Selling Price
- Average Monthly Revenue

---

## 💡 Advanced SQL Skills Demonstrated

Throughout this project, I applied several SQL techniques to solve analytical problems and generate business insights.

| SQL Technique | Application |
|---|---|
| Joins | Combining information from multiple related tables. |
| Aggregate Functions | Calculating total sales, orders, quantities, and averages. |
| CTEs | Structuring complex queries into readable and manageable steps. |
| Subqueries | Performing nested calculations and comparisons. |
| Window Functions | Calculating running totals, rankings, and performance metrics. |
| CASE WHEN | Implementing conditional logic and customer/product segmentation. |
| Date Functions | Performing time-based analysis and calculating customer lifespan. |
| GROUP BY | Summarizing business metrics across different dimensions. |
| DISTINCT | Counting unique customers and products. |
| NULLIF | Preventing division-by-zero errors. |
| CAST | Handling data types and decimal calculations. |
| ROUND | Formatting calculated metrics. |

---

## 📁 Repository Structure

```text
sql-sales-data-analytics/
│
├── datasets/
│
├── scripts/
│   ├── 01_database_exploration.sql
│   ├── 02_dimensions_exploration.sql
│   ├── 03_date_range_exploration.sql
│   ├── 04_measures_exploration.sql
│   ├── 05_magnitude_analysis.sql
│   ├── 06_ranking_analysis.sql
│   ├── 07_change_over_time.sql
│   ├── 08_cumulative_analysis.sql
│   ├── 09_performance_analysis.sql
│   ├── 10_part_to_whole.sql
│   ├── 11_data_segmentation.sql
│   ├── 12_customer_report.sql
│   └── 13_product_report.sql
│
├── images/
│
└── README.md
```

## 📚 Key Learning Outcomes

Through this project, I strengthened my ability to:

- Explore and understand relational databases.
- Write structured and analytical SQL queries.
- Apply advanced SQL techniques to solve business problems.
- Analyze sales trends and business performance.
- Evaluate customer purchasing behavior and product performance.
- Calculate meaningful business KPIs.
- Transform raw data into structured information for analytical reporting.

---

**Author:** [Ansh Sharma](https://github.com/sanshh)

**GitHub:** [sanshh](https://github.com/sanshh)
