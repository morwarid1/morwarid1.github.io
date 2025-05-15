---
layout: post
title: 🗄️ Phase 3 | SQL & Databases  
excerpt: "Master the fundamentals of SQL and relational databases — from writing queries and joining tables to advanced transformations and performance optimization."
modified: 2/27/2021, 03:00:00
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: blog
---

![Pies](https://morwarid1.github.io/images/sql.png)  

Welcome to **Phase 3** of your data journey! In this module, you'll learn **Structured Query Language (SQL)** — a must-have skill for querying, analyzing, and managing relational databases.

Whether you're extracting customer behavior data or building automated reports, SQL is the language that brings your data to life.

---

## 1️⃣ SQL Basics

Start with the essentials of querying a relational database.

- 🏗️ **What is SQL?** Introduction to relational databases & SQL structure  
- 📥 **SELECT Statements** – Extract columns from tables  
- 🧮 **Filtering** – Use `WHERE` clauses for targeted results  
- 📊 **Aggregation** – `GROUP BY` and `HAVING` to summarize data  
- 🔢 **Sorting & Limiting** – `ORDER BY` and `LIMIT` to control output  
- 🧠 **Conditional Logic** – Use `CASE` statements for if/then logic  

💡 *Think of SQL as asking structured questions to your database and getting specific answers.*

---

## 2️⃣ Working with Multiple Tables

Real-world data is spread across multiple tables. Here's how to combine it effectively:

- 🔗 **Relationships**: Understand One-to-One, One-to-Many, and Many-to-Many relationships  
- 🤝 **JOINs**: Master `INNER`, `LEFT`, `RIGHT`, and `FULL OUTER` JOINs  
- 📦 **Subqueries**: Write nested queries for more complex logic  
- 🧩 **Set Operations**: Use `UNION`, `INTERSECT`, and `EXCEPT` to combine query results  

---

## 3️⃣ Data Aggregation & Filtering

Learn to summarize and filter data effectively for insights:

- ➕ Aggregation functions: `SUM()`, `AVG()`, `COUNT()`, `MIN()`, `MAX()`  
- 🎯 Filter after grouping with `HAVING` vs. before grouping with `WHERE`  
- 🧠 Conditional Aggregation: Apply logic inside aggregation (e.g., `COUNT(CASE WHEN...)`)  

🧩 These techniques are the building blocks of dashboards, reports, and deep dives.

---

## 4️⃣ Advanced SQL & Data Transformation

Push your SQL skills further with these powerful tools:

### 🪟 Window Functions

- Rank, sort, and perform calculations across partitions of your data using:
  - `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`, `NTILE()`
  - `LEAD()` and `LAG()` for comparing rows

### 🧱 Common Table Expressions (CTEs)

- Write cleaner queries with reusable logic using `WITH` clauses
- Create **recursive CTEs** for hierarchical data

### 🧼 Data Cleaning with SQL

- Handle:
  - **Missing values** – `COALESCE()`  
  - **Duplicate entries** – `ROW_NUMBER()` filtering  
  - **Text cleanup** – `TRIM()`, `REPLACE()`, `LOWER()`, etc.  

---

## 🚀 Query Optimization & Performance

Make your SQL run faster and scale better:

- ⚡ **Indexing** for quicker searches  
- 🛑 Avoid `SELECT *` — specify only what you need  
- 🧩 Use appropriate **data types** and constraints  
- 🔍 Learn how to **read execution plans** and optimize queries  

---

## 🎯 What’s Next?

By completing this phase, you’ll be comfortable querying structured data, building complex logic, and optimizing performance — essential for roles in data analysis and BI.

In **Phase 4**, we’ll dive into **Python for Data Analysis** and bring automation and flexibility to your data workflows.

## Project: "Customer Insights from an Online Store Database"

Objectives:

- Write SQL queries to answer:

-- Top 5 customers by spending

-- Most returned products

-- Monthly revenue trends

- Use JOIN, GROUP BY, ORDER BY, subqueries

- Bonus: Use SQLite or PostgreSQL and connect to Python or Power BI

> *Structured data, structured thinking. Let SQL be your superpower in data analysis.*


