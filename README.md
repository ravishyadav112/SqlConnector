# 📊 Task 7: Basic Sales Summary using MySQL and Python

## 🔍 Objective
- Connect MySQL with Python using `mysql-connector-python`
- Insert and query sales data
- Calculate total quantity sold and revenue by product
- Visualize the result using a bar chart (Matplotlib)

---

## 🛠 Tools Used
- MySQL
- Python (Jupyter Notebook)
- mysql-connector-python
- pandas
- matplotlib

---

## 📋 What I Did

1. **Created a Database & Table**
   - Database: `sales_db`
   - Table: `sales(id, product, quantity, price)`

2. **Inserted Sample Data**
   ```python
   data = [
       ("Apples", 10, 2.5),
       ("Bananas", 5, 1.0),
       ("Oranges", 8, 1.8),
       ("Apples", 6, 2.5),
       ("Bananas", 7, 1.0),
       ("Grapes", 12, 3.0),
       ("Oranges", 5, 1.8),
   ]
