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

- 📁 Dataset

The project uses a relational sales database containing information
about orders, products, categories, customers, salespersons, and
regions.

The data is analyzed using MySQL.

🗄️ Database Tables

The project uses the following tables:

| Table | Purpose |
| Orders | Contains order and sales transaction information |
| Products | Contains product details |
| Categories | Contains product category information |
| Customers | Contains customer information |
| Salespersons | Contains salesperson information |
- Calculating sales contribution percentages
- Identifying top customers by region
- Identifying important sales performance patterns

- 🧠 SQL Concepts Used

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

- ❓ Business Questions Answered

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

  📈 Key Analysis Areas

 Product Analysis
- Highest-selling product
- Lowest-selling product
- Products performing above category average

 Category Analysis
- Highest-selling category
- Category sales contribution
- Monthly category ranking
- Regional category contribution

Salesperson Analysis
- Salesperson order volume
- Salesperson sales performance
- Salespersons performing above regional average

 Customer Analysis
- Top customers by region
- Customer sales performance

Regional Analysis
- Regional sales performance
- Category contribution within each region

Time-Based Analysis
- Monthly sales
- Monthly sales growth
- Month-over-month growth
- Running total sales
- Highest-selling month
- Highest monthly growth

- 🔍 Key Findings

The analysis identified several important sales patterns:

- The highest-selling product was **[Product Name]** with total sales
  of **[Amount]**.

- The lowest-selling product was **[Product Name]** with total sales
  of **[Amount]**.

- The highest-selling category was **[Category Name]** with total sales
  of **[Amount]**.

- The salesperson with the highest number of orders was
  **[Salesperson Name]** with **[Number]** orders.

- The highest-selling month was **[Month/Year]** with total sales of
  **[Amount]**.

- The month with the highest sales growth was **[Month/Year]** with
  **[Percentage]%** growth.

   ## 🛠️ Tools & Technologies

- **Database:** MySQL
- **Language:** SQL
- **Data Analysis:** Aggregation, Joins, Subqueries, CTEs, Window Functions
- **Data Visualization:** Canva
- **Version Control:** GitHub

- 📂 Project Structure

```text
SQL-Sales-Analysis-Project/
│
├── README.md
│
├── SQL/
│   └── Sales_Analysis_Project.sql
│
└── Dataset/
    └── Sales_Analysis_Dataset.xlsx

# 13. How to Run

This is useful for recruiters who want to test your project.

Add:

```markdown
## ▶️ How to Run

1. Install MySQL and MySQL Workbench.
2. Create the required database.
3. Create/import the required tables.
4. Load the dataset into the database.
5. Open `SQL/Sales_Analysis_Project.sql`.
6. Execute the queries in MySQL Workbench.
7. Review the results for each business question.

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

The analysis covers product, category, customer, salesperson,
regional, and time-based sales performance.

The project demonstrates practical SQL skills that can be applied
to real-world business and sales analysis scenarios.
