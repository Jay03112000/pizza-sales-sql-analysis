# 🍕 Pizza Sales Analysis using SQL

Welcome to the **Pizza Sales Analysis** project – a full-stack SQL data exploration case study using real-world-style data. This project uncovers business insights for a fictional pizza company by analyzing customer orders, sales trends, and product performance using **SQL**, supported by visuals and a professional report.

---

## 📊 Project Highlights

- 📦 **Dataset**: Orders, Pizza Types, Pizzas, and Order Details
- 💾 **Tools Used**: SQL (PostgreSQL/MySQL), Excel, Matplotlib, Word
- 📈 **Visuals Included**: ER Diagram, Revenue Share, Top Pizza Types, Hourly Orders
- 📘 **Report**: Full professional report with SQL queries, results, insights, and visuals

---

## 🧠 Business Questions Answered

### 🟢 Basic Level
- ✅ Total number of orders placed
- 💰 Total revenue generated from pizza sales
- 🧀 Highest-priced pizza and most common size
- 🔝 Top 5 most ordered pizza types

### 🟡 Intermediate Level
- 🍗 Total quantity ordered by pizza category
- 🕒 Distribution of orders by hour
- 🍕 Category-wise pizza variety
- 📆 Daily average number of pizzas ordered
- 💸 Top 3 pizzas by total revenue

### 🔴 Advanced Level
- 📊 Revenue contribution by category
- 📈 Cumulative revenue over time
- 🥇 Top 3 pizzas by revenue per category using window functions

---

## 📁 Project Structure
pizza-sales-sql-analysis/ │ ├── README.md # You're here! ├── ER_diagram.png # Entity-Relationship diagram ├── charts/ │ ├── top5_pizzas.png │ ├── revenue_by_category.png │ └── hourly_orders.png ├── queries/ │ ├── basic_queries.sql │ ├── intermediate_queries.sql │ └── advanced_queries.sql └── Pizza_Sales_Analysis_Report.docx # Full analysis report with visuals and SQL


---

## 📘 Key SQL Techniques Used

- ✅ `JOIN` across multiple related tables
- 🧮 `GROUP BY` with `SUM()`, `COUNT()`, `AVG()`
- 🪟 Window functions: `RANK()`, `SUM() OVER`
- 🗓️ Date/time extraction: `HOUR()`, `DAY()`
- 🔄 Subqueries and Common Table Expressions (CTEs)

---

---

## 🚀 Getting Started

1. Clone this repo
2. Load the data into your SQL environment
3. Run queries from `queries/` folder
4. Read the full report for insights
5. Use or extend this project for your portfolio!

```bash
git clone https://github.com/yourusername/pizza-sales-sql-analysis.git

