# Analyze Data in a Model Car Database (SQL)

**Author:** Anita C. Carrasco  
**Tools:** MySQL Workbench, SQL  
**Dataset:** Classic Models / MintClassics (Model Car Database)

---

## 📌 Overview
This project analyzes a model car sales database using SQL to uncover revenue patterns across products, product lines, and warehouses. The objective is to demonstrate practical SQL skills, including table exploration, joins, aggregations, and business-focused analysis.

The analysis follows a structured workflow commonly used in real-world data analysis projects, separating exploration, analysis, and final reporting queries.

---

## 🧱 Database Structure
Key tables used in the analysis include:

- `products`
- `orderdetails`
- `orders`
- `warehouses`
- `productlines`

Revenue is calculated using:

```text
quantityOrdered × priceEach
```

---

## 🧭 Project Structure

01_exploration.sql     # Data understanding and table exploration

02_analysis.sql        # Revenue analysis and aggregations

03_final_queries.sql   # Polished, portfolio-ready queries

```markdown
model-car-sql-analysis/
├── 01_exploration.sql
├── 02_analysis.sql
└── 03_final_queries.sql
```
---

## 📊 Key Analyses

### 🔹 Top Revenue-Generating Products
Identifies which individual products generate the highest total revenue.

### 🔹 Revenue by Product Line
Shows that **Classic Cars** and **Vintage Cars** dominate overall revenue, indicating the company’s core business focus.

### 🔹 Revenue by Warehouse
Reveals that the **East warehouse** is the top-performing distribution center, suggesting higher demand concentration or more efficient operations.

---

## 📈 Key Insights

- Classic Cars are the primary revenue driver.
- A small number of high-performing products account for a large share of sales.
- Revenue distribution varies significantly by warehouse, highlighting operational and logistical considerations.

---

## 🧠 Conclusion
This project demonstrates the use of SQL to translate raw transactional data into actionable business insights. By combining structured exploration with targeted analytical queries, it showcases practical skills relevant to data analyst and business intelligence roles.

---

