# Sql_Data_Analysis
 SQL-powered analysis of the Brazilian E-Commerce (Olist) dataset using PostgreSQL to uncover customer, product, and sales insights.
# 🛒 Brazilian E-Commerce (Olist) - SQL Data Analysis

## 📌 Project Overview

This project explores the Brazilian E-Commerce Public Dataset (Olist) using **PostgreSQL** to perform structured data analysis. It involves querying multiple interrelated tables to generate insights into customer behavior, product performance, delivery delays, and overall platform metrics.

---

## 💾 Dataset Description

The dataset was sourced from Kaggle: [Olist E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

It contains 100k+ rows across multiple tables, including:
- `orders`
- `customers`
- `order_items`
- `order_reviews`
- `order_payments`
- `products`
- `sellers`
- `geolocation`
- `product_category_name_translation`

---

## 🧠 Goals

- Understand customer order behavior
- Analyze delivery performance and delays
- Study review scores and satisfaction levels
- Identify best-selling products and categories
- Evaluate payment methods and transaction values

---

## 🛠️ Tech Stack

- **Database**: PostgreSQL 17
- **Interface**: pgAdmin 4
- **Language**: SQL (DDL + DML)
- **Environment**: Local server

---

## 📈 Key SQL Concepts Used

- ✅ Table creation and data import using `COPY`
- ✅ INNER / LEFT JOINS across relational tables
- ✅ Aggregate functions like `SUM()`, `AVG()`, `COUNT()`
- ✅ Subqueries and nested logic
- ✅ Views for reusable logic
- ✅ Basic indexing for performance

---

## 📊 Analysis Highlights

| 🔍 Query | Description |
|---------|-------------|
| Delivered Orders Count | Total number of successful deliveries |
| Avg Delivery Time | Time taken from purchase to customer delivery |
| Top Reviewers | Customers who submitted most reviews |
| Revenue Insights | Total and average payment per order |
| Category Popularity | Best-selling product categories |
| Monthly Order Volume | Time trend of order counts |

---

## 📸 Screenshots of SQL Queries & Results

### 1. Total Orders Delivered
![Total Orders Delivered]("C:\Users\Asus\OneDrive\Pictures\Screenshots\Screenshot 2025-04-25 162057.png")

---

