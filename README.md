# SQLite-Database-using-Python
#  Basic Sales Summary using SQLite, Python, Pandas, and Matplotlib

##  Project Overview

This project demonstrates how to:
- Create a simple SQLite database (`sales_data.db`)
- Store basic sales data in a table (`sales`)
- Use SQL queries in Python to calculate total quantity sold and total revenue per product
- Display the results using `print()` and visualize with a bar chart using `matplotlib`

---

## Files Included

- `sales_data.db` — SQLite database with sample sales data
- `sales_summary.py` — Python script to create database, query data, and visualize
- `sales_chart.png` — Bar chart showing revenue per product (auto-generated)
- `README.md` — This file

---

## 🛠Tools & Libraries Used

- Python (built-in `sqlite3` module)
- `pandas` for data handling
- `matplotlib` for visualization
- SQLite (no external setup needed)

---

## Sales Table Structure

| Column   | Type    | Description             |
|----------|---------|-------------------------|
| id       | INTEGER | Auto-incremented ID     |
| product  | TEXT    | Name of the product     |
| quantity | INTEGER | Quantity sold           |
| price    | REAL    | Price per unit          |

---

##  How It Works

1. **Database Creation & Data Insertion**
   - A new SQLite database `sales_data.db` is created
   - A `sales` table is created and filled with sample product sales data

2. **Data Analysis**
   - SQL query aggregates:
     - Total quantity sold per product
     - Total revenue (quantity × price) per product

3. **Results Displayed**
   - Console output using `print()`
   - Revenue bar chart using `matplotlib`

---

