# Task_2-DA-
# 📊 Superstore Sales Dashboard (Power BI)

This project showcases an interactive and insightful **Sales Dashboard** created in **Power BI**, using the popular **Superstore** dataset. The goal is to visualize key business metrics and enable better data-driven decisions.

---

## 🧩 Features Included

- ✅ KPIs: Total Sales, Profit, Count of Regions & Categories  
- 📅 Dynamic Filters: Year, Month, State, City, Region  
- 📊 Visuals:
  - Category-wise Sales Distribution
  - Year-wise Sales by Segment
  - Total Sales by City
  - Sales by Segment (Donut Chart)
  - Top 10 Sub-Categories by Sales

---

## 🗃️ Dataset Details

- Cleaned in Excel & Python (due to inconsistent date formats)
- Final dataset: `Superstore_Cleaned_Short.csv`

---

## 🧼 Data Cleaning Summary

- Dates had mixed formats (e.g. `11/08/2016`, `4-15-2017`, `8/27/2014`)
- Cleaned using Python:
```python
df['Order Date Cleaned'] = df['Order Date'].astype(str).str.replace('-', '/')
df['Order Date Cleaned'] = pd.to_datetime(df['Order Date Cleaned'], errors='coerce')

## 📊 **Dashboard Description**

**The Superstore Sales Dashboard** is an interactive Power BI report that delivers a comprehensive view of sales performance across various dimensions such as **Category**, **Region**, **City**, and **Customer Segment**.

It includes:

- **Key KPIs**: Total Sales, Total Profit, Count of Regions & Categories
- **Interactive Filters**: Year, Month, State, City, Region
- **Visuals**:
  - Category-wise Sales Distribution
  - Year-wise Total Sales by Segment
  - Top 10 Cities by Sales
  - Sales by Segment (Donut Chart)
  - Sales of Top 10 Sub-Categories

This dashboard enables users to **explore trends**, **compare categories**, and **gain actionable insights** to support business decision-making.

The dataset used was cleaned using Python to resolve inconsistent date formats before loading into Power BI.
