# Task 7 – Sales Summary (Data Analyst Internship)

## 📌 Objective
Use SQL inside Python to pull simple sales info (like total quantity sold, total revenue), and display it using basic print statements and a bar chart.

---

## 🛠 Tools
- Python (sqlite3, pandas, matplotlib)
- SQLite (comes with Python, no extra setup required)

---

## 📂 Files in this Repo
- `sales_data.db` → SQLite database with sample sales data
- `task7_sales_summary.py` → Python script to run SQL queries and generate chart
- `sales_chart.png` → Revenue bar chart output
- `sales_summary.txt` → Printed summary output
- `README.md` → Documentation

---

## ▶️ Steps to Run
1. Clone/download this repository.
2. Ensure you have Python installed with `pandas` and `matplotlib`:
   ```bash
   pip install pandas matplotlib
   ```
3. Run the Python script:
   ```bash
   python task7_sales_summary.py
   ```

---

## 📊 Expected Output
**Printed Table (example):**
```
     product   total_qty   revenue
0  Headphones        15     30000
1      Laptop         7    420000
2       Phone        13    390000
```

**Bar Chart:**  
A bar chart showing revenue by product (Laptop, Phone, Headphones).

---

