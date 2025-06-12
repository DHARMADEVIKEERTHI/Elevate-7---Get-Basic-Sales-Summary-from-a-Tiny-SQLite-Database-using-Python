# TASK 7 - Basic Sales Summary Using SQLite and Python

## 🔍 Objective
Use SQL within Python to extract total quantity sold and revenue per product from a small sales database and visualize the results.

---

## 🧰 Tools Used
- Python
- SQLite (`sqlite3`)
- Pandas
- Matplotlib

---

## 📁 Files
- Elevate 7 Sales data.ipynb
---

## 🧑‍💻 What I Did
1. Created a SQLite database and added a `sales` table with product, quantity, and price.
2. Used SQL inside Python to calculate:
   - Total Quantity
   - Revenue = `SUM(quantity * price)`
3. Loaded results using `pandas`
4. Plotted bar chart using `matplotlib`

---

## 📊 Sample Output

| product          | total_qty | revenue |
|------------------|-----------|---------|
| Apple iPhone 14  | 7         | 5593.0  |
| Sony WH-1000XM5  | 16        | 5600.0  |


