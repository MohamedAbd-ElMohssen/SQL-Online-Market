# SQL-Online-Market
Built a complete SQL-based data warehouse from raw retail data, including data cleaning, star schema modeling, ETL pipelines, and business analytics using advanced SQL.

## 📌 Overview
This project demonstrates a complete data engineering workflow using SQL, starting from raw data ingestion to building a star schema data warehouse and generating business insights.

---

## 🏗️ Project Architecture

1. Raw Data (CSV)
2. Staging Layer (Data Cleaning)
3. Data Modeling (Star Schema)
4. Data Warehouse (Fact & Dimensions)
5. Analytics Queries

---

## 🧩 Data Model

- Fact Table:
  - fact_sales

- Dimension Tables:
  - dim_product
  - dim_customer
  - dim_date

---

## ⚙️ ETL Process

- Handled missing and inconsistent data
- Converted data types using TRY_CAST
- Removed invalid records (negative values, nulls)
- Built staging table
- Populated dimensions using DISTINCT and GROUP BY
- Loaded fact table using JOINs (key mapping)

---

## 📊 Business Insights

### 🔝 Top Customers
- Identified highest revenue customers

### 📅 Monthly Revenue Trend
- Analyzed sales performance over time

### 🛍️ Best Selling Products
- Found top revenue-generating products

### 🌍 Revenue by Country
- Compared performance across regions

### 📈 Running Total
- Calculated cumulative revenue using window functions

---

## 🧠 Skills Demonstrated

- SQL Data Cleaning
- Data Modeling (Star Schema)
- ETL Pipeline Design
- Joins & Aggregations
- CTEs & Window Functions
- Analytical Thinking

---

## 🚀 Tools Used

- SQL Server
- SSMS

---

## 📎 How to Run

1. Import the dataset into SQL Server
2. Run SQL scripts in order:
   - Data Understanding
   - Cleaning
   - Modeling
   - ETL
   - Analytics

---

## 👨‍💻 Author

Your Name
