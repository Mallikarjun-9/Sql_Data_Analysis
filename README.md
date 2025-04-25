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
![image_alt](https://github.com/Mallikarjun-9/Sql_Data_Analysis/blob/62081c4500c5a96b488a4e0f0b2bb6c2cc5a4f20/Screenshot%202025-04-25%20162129.png)

---

### 2. Average Delivery Time
![Average Delivery Time](https://github.com/Mallikarjun-9/Sql_Data_Analysis/blob/77d17cf824eb43d06633804ea56ac5a05349cc9e/Screenshot%202025-04-25%20162216.png)

---

### 3. Top 5 States by Number of Orders
![Top States by Orders](https://github.com/Mallikarjun-9/Sql_Data_Analysis/blob/b43a13bc2659e46f98b5d27aa649570a0fe98eb5/Screenshot%202025-04-25%20162308.png)

---

### 4. Most Used Payment Types
![Most Used Payment Types](screenshots/04_payment_types.png)

---

### 5. Top Rated Products (Avg Review Score)
![Top Rated Products](screenshots/05_top_rated_products.png)

---

### 6. Monthly Order Trends
![Monthly Order Trends](screenshots/06_monthly_orders.png)

---

### 7. Top Selling Product Categories
![Top Product Categories](screenshots/07_top_categories.png)

---

### 8. Most Active Sellers
![Most Active Sellers](screenshots/08_top_sellers.png)

---

### 9. Revenue Summary (Optional)
![Revenue Summary](screenshots/09_revenue_summary.png)

---

### 10. Customers with Most Reviews (Optional)
![Top Reviewers](screenshots/10_top_reviewers.png)
