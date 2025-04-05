# Retail_Sales_Analysis

# 🛍️ Retail Sales Analysis – SQL + Power BI Project

## 📌 Project Overview
This end-to-end project analyzes retail sales data using SQL and Power BI. It showcases how raw transactional data can be transformed, analyzed, and visualized to uncover insights around customer behavior, category performance, and sales trends.
  
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

## 📈 Power BI Dashboard

### 🔹 Page 1: Sales Overview  
**Goal:** Show KPIs and category-level performance.  

**Visuals:**  
- **KPI Cards**: Total Sales, Profit, Orders, Profit Margin  
- **Line Chart**: Sales over Time  
- **Bar Chart**: Top Product Categories  

---

### 🔹 Page 2: Customer Demographics  
**Goal:** Understand who the customers are.  

**Visuals:**  
- **Pie Chart**: Gender Distribution  
- **Histogram**: Age Distribution  
- **Bar Chart**: Sales by Age Group  
- **Scatter Plot**: Age vs. Average Purchase Value  
  - **Y-Axis**: `total_sales / COUNT(customer_id)`

---

### 🔹 Page 3: Profit & Cost Analysis  
**Goal:** Understand profitability and cost dynamics.  

**Visuals:**  
- **Bar/Column Chart**: Profit by Category  
- **Combo Chart**: Sales vs. COGS  
- **Line Chart**: Monthly Profit Trend  

---

### 🔹 Page 4: Time-Based Insights  
**Goal:** Understand when sales happen.  

**Visuals:**  
- **Bar Chart**: Orders by Shift (Morning, Afternoon, Evening)  
- **Line Chart**: Daily Sales Trend  
- **Heatmap**: Sales by Day and Hour  

---

### 🔍 Key Insights  
- **Customer Behavior**: Ages 26–35 are most active  
- **Sales Trends**: Seasonal patterns with clear peaks  
- **Top Products**: Clothing & Beauty dominate  
- **Time Patterns**: Evening sales highest  

---
