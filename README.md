# 🛍 Retail Sales Optimization — Data Analytics Project

### 📊 Data Cleaning (Python) | 📈 Business Insights (SQL) | 📉 Profitability Analysis (BI)

---

## 📌 Project Overview

Retail businesses often struggle to balance revenue growth, product demand, inventory, and regional sales performance.
This project performs **end-to-end analytics** on a sales dataset by:

✔ Profiling and Cleaning data in Python
✔ Feature Engineering (Sale Price & Profit Calculation)
✔ Insightful SQL Analysis for Business Decisions

---

## 🎯 Business Objectives

* Understand **product-wise and region-wise sales trends**
* Identify **top revenue drivers**, **high-profit categories**, and **growing segments**
* Detect **seasonal sales patterns** and inventory opportunities
* Enable **data-backed marketing and supply chain decisions**

---

## 🗂 Dataset Details

**Source:** Provided retail order dataset
**Rows:** 9,994
**Columns:** 16

### Key Columns

* Order ID, Order Date, Ship Mode
* Product Category, Sub-Category
* Cost Price, List Price, Discount %, Profit, Quantity
* Customer Segment, Region, City, State

---

## 🔍 Data Profiling & Cleaning (Python)

Performed inside **Retail.ipynb**:

| Task                      | Output                        |
| ------------------------- | ----------------------------- |
| Checked datatypes & nulls | 1 missing Ship Mode → Imputed |
| Fixed datatypes           | Order Date → datetime         |
| Created KPIs              | `Sale Price`, `Profit`        |
| Outlier scan              | No invalid orders             |
| Standardization           | Uniform casing in text values |

### Engineered Columns

```text
Sale Price = List Price * (1 - Discount % / 100)
Profit = Sale Price - Cost Price
```

---

## 🧮 MySQL Data Modeling & Queries

SQL Stored in: `Order_queries.sql`

Highlights:

| Query Category               | Purpose                         |
| ---------------------------- | ------------------------------- |
| Top revenue products         | Market demand targeting         |
| Monthly trend 2022 vs 2023   | Forecasting                     |
| Category-wise best month     | Seasonal campaigns              |
| Profitability by region/city | Location performance            |
| Sub-category YoY growth      | Product investment decisions    |
| Shipment & segment mix       | Customer experience improvement |

Uses:

* CTEs
* Window Functions
* Grouping analytics
* Time-series comparison

---

## 📊 Key Business Insights

| Area            | Insight                                | Recommendation            |
| --------------- | -------------------------------------- | ------------------------- |
| Product Revenue | Few products drive majority revenue    | Boost stock & promo focus |
| Regional Demand | Strong variation in product popularity | Region-specific marketing |
| Seasonality     | Category peaks differ by month         | Smart inventory rotation  |
| Profitability   | Some low-sales SKUs = high margin      | Profit-driven bundles     |
| Customer mix    | Corporate/B2B brings higher revenue    | Loyalty program expansion |

---

## 🛠 Tools & Technologies

| Tool                          | Usage                         |
| ----------------------------- | ----------------------------- |
| Python (Pandas, NumPy)        | Data cleaning, transformation |
| MySQL                         | Insight extraction            |
| Jupyter Notebook              | EDA execution                 |
| GitHub                        | Version control & publishing  |

---

## 📁 Repository Structure

```
📦 Retail-Sales-Analytics
 ┣ 📄 orders.csv
 ┣ 📄 Retail.ipynb
 ┣ 📄 Order_queries.sql
 ┣ 📄 README.md  ⬅ You are here
```

---

## 👨‍💻 Author

**Mandar Manjare**
📍 Data Analyst | SQL | Python | Business Intelligence

📧 Email: *mandar.manjare07@gmail.com*
🔗 LinkedIn: *www.linkedin.com/in/mandar-manjare

---

## 🏁 Conclusion

This project successfully demonstrates the use of:

> **Python for data hygiene** +
> **SQL for strategic business intelligence**
> A great showcase for Data Analyst / Business Analyst roles 🎯

---

