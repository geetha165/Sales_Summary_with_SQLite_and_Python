# ElevateLabs_Internship_Task-7
Get Basic Sales Summary from a Tiny SQLite Database using Python Objective: Use SQL inside Python to pull simple sales info (like total quantity sold, total revenue), and display it using basic print statements and a simple bar chart.
# 📊 Sales Summary with SQLite and Python

This project demonstrates how to build a basic sales summary report using Python, SQLite, pandas, and matplotlib. The script connects to a local SQLite database, runs SQL queries to calculate key sales metrics, and displays the results in both text and a bar chart. Additionally, it calculates the average price per product and exports the summary to a CSV file.

---

##  Tools Used
- Python 3(Jupyter)
- SQLite3 (built-in)
- pandas
- matplotlib

---

##  Database Schema

**Table: `sales`**
| Column     | Type     | Description         |
|------------|----------|---------------------|
| id         | INTEGER  | Primary Key         |
| product    | TEXT     | Product name        |
| quantity   | INTEGER  | Units sold          |
| price      | INTEGER  | Price per unit (in local currency) |

---

##  What the Script Does

1. Connects to (or creates) a SQLite database `sales_data.db`
2. Creates a `sales` table if it doesn't exist
3. Inserts sample product sales data
4. Executes a SQL query to:
   - Sum total quantity sold per product
   - Compute total revenue per product (`quantity * price`)
   - Calculate average price per product
5. Displays results in the terminal
6. Plots a bar chart of revenue per product
7. Exports the sales summary to a CSV file `sales_summary.csv`

---



