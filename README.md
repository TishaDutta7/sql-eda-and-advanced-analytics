# SQL Exploratory Data Analysis & Advanced Analytics
<img width="2141" height="818" alt="Project Roadmap (1)" src="https://github.com/user-attachments/assets/094c307c-1ea1-4bad-87c8-1d88da0c31c0" />

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** and **Advanced Analytics** using **SQL Server (T-SQL)** on a structured analytical dataset.

The goal is to demonstrate how SQL can be used not just for querying data, but for **business understanding, insight generation, and analytical reasoning** by systematically exploring dimensions, measures, time ranges, and relationships within the data.

This repository is a continuation of the analytical layer built on top of a previously designed **SQL Data Warehouse (Medallion Architecture)**, where clean **Gold layer views** are used as the analytical source.

---

## 🧠 Analytical Framework Used

The analysis follows a **business-driven SQL EDA framework**, commonly used by data analysts and analytics engineers:

1. **Database Exploration**
2. **Dimension Exploration**
3. **Date Exploration**
4. **Measures Exploration**
5. **Magnitude Analysis**
6. **Ranking & Comparative Analysis**

This structured approach ensures no blind querying and helps uncover meaningful insights efficiently.

---

## 🗂️ Data Source

* Source data comes from **Gold Layer views** created in a SQL Data Warehouse.
* Views used include:

  * `gold.dim_customers`
  * `gold.dim_products`
  * `gold.fact_sales`

These views represent **clean, standardized, and business-ready data**, enabling accurate analysis.

---

## 🔍 Key Analysis Sections

### 1️⃣ Database Exploration

* Identified available tables, views, and schemas
* Explored table structures using `INFORMATION_SCHEMA.TABLES`
* Inspected column metadata using `INFORMATION_SCHEMA.COLUMNS`
* Understood data types, nullability, and granularity

---

### 2️⃣ Dimension Exploration

Explored unique values and granularity for key dimensions such as:

* Country
* Product category & subcategory
* Product names
* Customers

This step helps understand **how the business operates across different segments**.

---

### 3️⃣ Date Exploration

* Identified earliest and latest dates using `MIN()` and `MAX()`
* Determined the time span of the business
* Validated date consistency across datasets

---

### 4️⃣ Measures Exploration

Calculated key business metrics using aggregate functions:

* Total sales
* Total quantity sold
* Average price
* Number of orders
* Number of customers
* Number of products

Also combined multiple KPIs into unified reports using `UNION ALL`.

---

### 5️⃣ Magnitude Analysis

Analyzed how metrics vary across different dimensions:

* Revenue by country
* Revenue by product
* Revenue by customer
* Customer distribution across regions

This step focuses on **comparing scale and impact**.

---

### 6️⃣ Ranking & Advanced Analytics

* Top and bottom performing products
* High-value customers
* Country and category rankings
* Comparative insights using `ORDER BY`, `GROUP BY`, and window functions

This phase moves beyond EDA into **decision-support analytics**.

---

## 🛠️ Skills & Concepts Demonstrated

* SQL Exploratory Data Analysis (EDA)
* Business-driven analytical thinking
* Aggregations & grouping
* Subqueries & CTEs
* Window functions
* Dimensional vs measure separation
* Insight generation using SQL
* Analytical storytelling through queries

---

## 📁 Repository Structure

```
sql-eda-and-advanced-analytics/
│
├── sql_eda_and_advanced_analytics.sql   -- Complete EDA & analytics queries
├── README.md                            -- Project documentation
```

---

