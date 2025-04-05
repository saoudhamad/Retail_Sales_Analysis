# Retail_Sales_Analysis

# 🛍️ Retail Sales Analysis – SQL + Power BI Project

## 📌 Project Overview
This end-to-end project analyzes retail sales data using SQL and Power BI. It showcases how raw transactional data can be transformed, analyzed, and visualized to uncover insights around customer behavior, category performance, and sales trends.

- **Level**: Beginner  
- **Tools**: PostgreSQL (SQL), Power BI  
- **Dataset**: Simulated retail sales data  

---

## 🎯 Objectives

- Set up and query a structured retail database  
- Clean and prepare the data using SQL  
- Explore sales, customer, and product trends  
- Build an interactive dashboard in Power BI for business stakeholders  

---

## 🗂️ Dataset Description

| Column             | Description                                  |
|--------------------|----------------------------------------------|
| `transactions_id`  | Unique transaction identifier                |
| `sale_date`        | Date of the transaction                      |
| `sale_time`        | Time of transaction                          |
| `customer_id`      | Unique customer identifier                   |
| `gender`           | Gender of customer                           |
| `age`              | Age of the customer                          |
| `category`         | Product category                             |
| `quantity`         | Quantity of items purchased                  |
| `price_per_unit`   | Unit price of the item                       |
| `cogs`             | Cost of goods sold                           |
| `total_sale`       | Total transaction value                      |

Derived columns:
- **Profit** = `total_sale - cogs`  
- **Profit Margin** = `(Profit / total_sale) * 100`

---
