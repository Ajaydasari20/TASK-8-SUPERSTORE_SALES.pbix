# 📊 Superstore Sales Dashboard - Power BI

An interactive Power BI dashboard to analyze Superstore sales performance across different regions, categories, and time.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `Superstore.csv` | Raw dataset used for analysis |
| `SUPERSTORE_SALES.pbix` | Power BI file with data cleaning & dashboard |
| `Screenshot.png` | Final dashboard screenshot |

---

## 📌 Dashboard Overview

![Dashboard Preview](./Screenshot.png)

### 🔍 Visuals Used:
- 📈 Line Chart: Sales Over Time (by Month-Year)
- 📊 Bar Chart: Sales by Region
- 🍩 Donut Chart: Sales by Category
- 📌 KPIs: Total Sales & Profits
- 📎 Slicer: Filter by Region or Category

---

## 🧹 Data Cleaning in Power BI

1. Imported `Superstore.csv` into Power BI.
2. Converted `Order Date` to `"Month-Year"` using DAX:
   ```DAX
   MonthYear = FORMAT('Superstore'[Order Date], "MMM-YYYY")
