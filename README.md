# 🛒 Retail Store Sales Database & Analytics

![SQL](https://img.shields.io/badge/Language-SQL-orange?style=for-the-badge&logo=mysql)
![Database](https://img.shields.io/badge/Database-Relational-blue?style=for-the-badge&logo=postgresql)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## 📄 Project Overview
This project involves the design, creation, and analysis of a relational database system for a retail business. I built a normalized schema to manage sales, customers, and inventory data, and performed exploratory data analysis (EDA) using complex SQL queries to derive actionable business insights.

The `.sql` file contains the complete source code for database architecture (DDL) and data manipulation/analysis (DML/DQL).

## 🎯 Objectives
* **Database Normalization:** Designed a schema to reduce redundancy and ensure data integrity using Primary and Foreign Keys.
* **Data Integrity:** Implemented constraints to validate data entry (e.g., `NOT NULL`, `CHECK`).
* **Business Intelligence:** Answered critical business questions regarding revenue, customer behavior, and product performance.

## 🗂️ Database Schema
The database consists of the following key tables:

* **`Customers`**: Stores customer demographics (ID, Name, Location, Join Date).
* **`Products`**: Manages inventory details (ID, Category, Price, Stock Level).
* **`Sales` / `Transactions`**: The core fact table recording individual purchase events linked to customers and products.

## 🛠️ Tech Stack
* **Language:** SQL (Standard SQL)
* **Techniques Used:**
    * **DDL:** Creating tables with precise data types.
    * **Joins:** `INNER`, `LEFT`, and `RIGHT` joins to merge datasets.
    * **Aggregations:** `GROUP BY`, `SUM()`, `AVG()`, and `COUNT()` for reporting.
    * **Subqueries & CTEs:** For readable and modular code structures.

## 📊 Key Insights & Analysis
The SQL script addresses the following analytical scenarios:
1.  **Revenue Analysis:** Calculated total monthly revenue to track seasonal performance.
2.  **Customer Insights:** Identified the top 5 customers by total spending.
3.  **Inventory Management:** Queried products with low stock levels to trigger re-ordering.
4.  **Product Trends:** Determined which product categories drive the highest sales volume.

## 🚀 How to Run
1.  **Prerequisites:** Ensure you have a SQL environment installed (MySQL Workbench, PostgreSQL, or SQL Server).
2.  **Import:** Open the `retail_sales_schema.sql` file in your SQL editor.
3.  **Execute:** Run the script to initialize the database, populate tables, and execute the analysis queries.

## 👤 Author
**Dipjyoti Karmakar**
* **Role:** Data Analyst / Business Intelligence
* **Connect with me:** [LinkedIn Profile](https://www.linkedin.com/in/dipjyoti-karmakar-91050a37a)

---
*This project is part of my portfolio demonstrating skills in Database Design, SQL Querying, and Data Management.*
