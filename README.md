SQL Sales Analysis Project

📊 Project Overview

This project analyzes sales data using MySQL to identify important
business insights related to products, categories, customers,
salespersons, regions, and monthly sales performance.

The project contains 56 SQL queries ranging from basic SQL
operations to advanced analytical queries using CTEs, subqueries,
window functions, ranking, and sales growth calculations.

🎯 Business Objective

The main objective of this project is to use SQL to analyze sales
data and answer important business questions that can support
better decision-making.

The analysis focuses on:

- Identifying top and low-performing products
- Identifying high-performing categories
- Analyzing salesperson performance
- Understanding customer purchasing behavior
- Comparing regional sales performance
- Analyzing monthly sales trends
- Measuring month-over-month sales growth

## 📂 Dataset

The dataset contains 5 related tables used for sales performance analysis:

| Table | Description |
|---|---|
| `customers.csv` | Customer information |
| `products.csv` | Product details and pricing |
| `categories.csv` | Product category information |
| `salespersons.csv` | Salesperson information |
| `orders.csv` | Order transactions, quantities, prices, discounts, and sales amounts |

The tables are connected using primary and foreign key relationships and are analyzed using MySQL.
## 🧠 SQL Concepts Used

### Basic SQL
- SELECT
- WHERE
- ORDER BY
- GROUP BY
- DISTINCT
- LIMIT

### Aggregations
- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()

### Filtering
- HAVING
- IN
- NOT IN
- BETWEEN
- LIKE

### Joins
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN

### Conditional Logic
- CASE WHEN

### Advanced SQL
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- LAG()
- RANK()
- DENSE_RANK()
- PARTITION BY
- OVER()
- Running Totals

### Date Analysis
- YEAR()
- MONTH()

### Data Analysis
- Sales Growth
- Month-over-Month Growth
- Running Sales Total
- Sales Contribution %
- Regional Performance
- Product Ranking
- Category Ranking

## ❓ Business Questions Answered

The project answers business questions such as:

1. Which product generates the highest sales?
2. Which product generates the lowest sales?
3. Which category generates the highest sales?
4. Which salesperson handles the highest number of orders?
5. Which salespersons perform above their regional average?
6. Which products perform above their category average?
7. What is the monthly sales growth?
8. What is the month-over-month sales growth percentage?
9. What is the monthly running total of sales?
10. Which month has the highest sales?
11. Which category contributes the most to total sales?
12. Which category contributes the most sales within each region?
13. Who is the top customer in each region?
14. Which month experienced the highest sales growth?
15. How are sales distributed across regions and categories?

## 📈 Key Analysis Areas

## 🔍 Key SQL Analysis

The project includes SQL analysis covering:

- Total sales and order performance
- Monthly and yearly sales trends
- Top-performing products
- Product category performance
- Customer purchase analysis
- Salesperson performance and ranking
- Sales contribution by salesperson
- Discount and pricing analysis
- Sales growth calculations
- Ranking using SQL window functions
- CTE-based analytical queries
- Subquery-based business analysis

## 🔍 Key Findings

The analysis identified several important sales patterns:

- The highest-selling product was **Skipping Rope** with total sales of **568866.59**.
- The lowest-selling product was **Dumbbell Set** with total sales of **25977.04**.
- The highest-selling category was **Electronics** with total sales of **1681954.10**.
- The salesperson with the highest number of orders was **Salesperson 03** with **33** orders.
- The highest-selling month was **2025-04** with total sales of **1292670.81**.
- The month with the highest sales growth was **2025-08** with **48.71%** growth.

## 🛠️ Tools & Technologies

- **Database:** MySQL
- **Language:** SQL
- **Data Analysis:** Aggregation, Joins, Subqueries, CTEs, Window Functions
- **Data Visualization:** Canva
- **Version Control:** GitHub

## 📁 Project Structure

```text
Sales-Performance-Analysis-SQL/
│
├── Dataset/
│   ├── README.md
│   ├── categories.csv
│   ├── customers.csv
│   ├── orders.csv
│   ├── products.csv
│   └── salespersons.csv
│
├── README.md
└── Sales_Analysis_Project.sql

```

## ▶️ How to Run
Install MySQL and MySQL Workbench.
Create the required database.
Create/import the required tables.
Load the dataset into the database.
Open Sales_Analysis_Project.sql.
Execute the queries in MySQL Workbench.
Review the results for each business question.

💼 Skills Demonstrated

- SQL Data Analysis
- Relational Database Analysis
- Data Aggregation
- Data Filtering
- Multi-table Joins
- Business Problem Solving
- Sales Performance Analysis
- Customer Analysis
- Product Analysis
- Regional Analysis
- Time-Series Analysis
- Window Functions
- CTEs
- Subqueries
- Ranking
- KPI Analysis

🏁 Conclusion

This project demonstrates the use of SQL to transform raw sales
transaction data into meaningful business insights.

## ⭐ Project Highlights

- Designed and analyzed a relational sales dataset using MySQL.
- Performed sales, product, category, customer, salesperson, regional, and time-based analysis.
- Used **INNER JOINs, GROUP BY, HAVING, subqueries, CTEs, and window functions** for business analysis.
- Calculated monthly sales, month-over-month growth, running totals, and salesperson rankings.
- Analyzed customer and product performance to identify key business trends.
- Organized the complete project and dataset in GitHub for portfolio presentation.

The analysis covers product, category, customer, salesperson,
regional, and time-based sales performance.

The project demonstrates practical SQL skills that can be applied
to real-world business and sales analysis scenarios.
