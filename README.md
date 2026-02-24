# Sales Dashboard using Power BI

## 📌 Project Overview
This project demonstrates a complete data analysis workflow using Power BI,
starting from Excel datasets to an interactive dashboard.
The goal is to analyze sales performance from multiple dimensions
such as time, product, and region.

---

## 📂 Datasets
- `AdventureWorks_Database.xlsx`  
  Main dataset containing sales, products, customers, calendar, and territories data.
- `Budget.xlsx`  
  Budget data used for comparison and planning analysis.

All datasets are provided in Excel (.xlsx) format.

---

## 🧹 Data Preparation (Power Query)
Data cleaning and transformation were performed using Power Query:
- Promoted headers
- Corrected data types
- Removed duplicates and null values (Budget table only)
- Kept other tables unchanged as they were already clean

All transformation steps are documented in **Applied Steps**.

---

## 🧩 Data Modeling
The data model follows a **Star Schema** design:
- **Fact Table:** Sales
- **Dimension Tables:** Product, Customer, Calendar, Territories

Relationships are defined as One-to-Many to support efficient and accurate analysis.

---

## 📊 Dashboard Features
The Power BI dashboard includes:
- KPIs:
  - Total Sales
  - Total Quantity Sold
  - Number of Orders
- Sales trend over time
- Sales by product category
- Top 10 products by sales
- Sales by region
- Interactive filters (Year, Category, Region)

A preview of the dashboard is available in `dashboard.png`.

---

## 🔍 Key Insights
- Certain product categories contribute the majority of total sales
- Sales performance varies significantly by region
- A small number of products account for a large share of revenue

---

## 🛠️ Tools & Technologies
- Power BI
- Power Query
- Excel (.xlsx)

---

## 📁 Repository Files
- `Sales_Dashboard.pbix` : Power BI report file
- `AdventureWorks_Database.xlsx` : Main dataset



## 🔎 
Power BI, Data Analysis, Business Intelligence, Dashboard, Star Schema,
Excel Analytics, Sales Analysis
- `Budget.xlsx` : Budget dataset
- `dashboard.png` : Dashboard preview
