# 📊 Sales Summary from a SQLite Database using Python

Get Basic Sales Summary from a Tiny SQLite Database using Python.
**Objective:** Use SQL inside Python to pull simple sales info (like total quantity sold, total revenue), and display it using basic print statements and a simple bar chart.

---

## 📌 Project Overview

This project demonstrates how to create a **basic sales summary report** using Python, SQLite, pandas, and matplotlib.
The script connects to a local SQLite database, runs SQL queries to calculate key sales metrics, and displays the results in both text and a bar chart.
It also calculates the **average price per product** and exports the summary to a CSV file.

---

## 🛠 Tools Used

* **Python 3** (Jupyter Notebook or `.py` script)
* **SQLite3** (built-in)
* **pandas**
* **matplotlib**

---

## 📂 Database Schema

**Table: `sales`**

| Column   | Type    | Description                        |
| -------- | ------- | ---------------------------------- |
| id       | INTEGER | Primary Key                        |
| product  | TEXT    | Product name                       |
| quantity | INTEGER | Units sold                         |
| price    | INTEGER | Price per unit (in local currency) |

---

## 🚀 Workflow

1. Connect to (or create) `sales_data.db`
2. Create the `sales` table if it doesn’t exist
3. Insert sample sales data
4. Run SQL queries to:

   * Sum total quantity sold per product
   * Calculate total revenue per product (`quantity * price`)
   * Calculate average price per product
5. Display results in the terminal
6. Plot a bar chart of revenue per product
7. Export the sales summary to `sales_summary.csv`

---

## 🎯 Learning Outcomes

By completing this project, you will:

* Learn to write basic SQL queries inside Python
* Practice importing SQL data into pandas
* Perform simple data summaries
* Create a basic sales chart using matplotlib

---

## 📬 Connect with me on LinkedIn:
- <a href="https://www.linkedin.com/in/geetha-venkatesan2205/">👉 LinkedIn Profile</a>
