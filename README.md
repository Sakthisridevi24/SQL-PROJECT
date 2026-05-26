# 📊 SQL Case Study – E-Commerce Retail Analysis (Sample Superstore)

## 🔍 Project Overview

This project is a comprehensive SQL-based case study performed on a structured retail/e-commerce dataset (Sample Superstore) to simulate real-world business scenarios. The analysis focuses on customer behavior, sales trends, delivery performance, payment analysis, and business growth insights using SQL.

The project demonstrates practical SQL skills used in data analytics and business intelligence workflows.

---

## 🎯 Objectives

- Explore dataset structure and characteristics
- Analyze order trends across time periods and regions
- Study customer distribution and purchasing behavior
- Evaluate economic impact through payment and freight analysis
- Measure delivery performance against estimated timelines
- Examine payment methods and installment patterns

---

## 🛠 Tools & Technologies

- Google BigQuery
- SQL (Standard SQL)
- Google Sheets / Excel
- ChatGPT
- Claude AI
- Google Gemini

---

## 🗂 Dataset Information

### Database
`Google BigQuery`

### Dataset Schema
`case_study`

### Tables Used
- `customers`
- `orders`
- `payments`

---

## 📚 SQL Concepts Used

| SQL Concept | Usage |
|---|---|
| `INNER JOIN / LEFT JOIN` | Linking multiple tables |
| `GROUP BY / HAVING` | Aggregation and filtering |
| `CTEs (WITH clause)` | Multi-step calculations |
| `Subqueries` | Nested analysis |
| `EXTRACT()` | Date and time analysis |
| `DATE_DIFF()` | Delivery duration analysis |
| `CASE WHEN` | Time-of-day categorization |
| `UNION ALL` | Combining multiple query outputs |
| `COUNT(DISTINCT)` | Unique customer/order analysis |
| `INFORMATION_SCHEMA` | Metadata exploration |

---

# 📊 Case Study Breakdown

## 1️⃣ Data Exploration

### Tasks Performed
- Retrieved column data types using `INFORMATION_SCHEMA.COLUMNS`
- Identified order date range
- Counted orders by city and state

### Key Findings
- Earliest order date: `2016-09-04`
- Latest order date: `2018-10-17`

---

## 2️⃣ In-Depth Exploration

### Analysis Performed
- Year-over-year order trend analysis
- Monthly seasonality identification
- Order categorization by time of day

### Time-of-Day Distribution
| Time Period | Orders |
|---|---|
| Afternoon | 38,135 |
| Night | 28,331 |
| Morning | 27,733 |
| Dawn | 5,242 |

### Insight
Afternoon (13:00–18:00 hrs) is the peak order placement period.

---

## 3️⃣ E-Commerce Evolution Analysis

### Analysis Performed
- Month-on-month orders by state
- Customer distribution analysis across states

### Key Insight
- SP state recorded the highest customer count with **40,302 unique customers**

---

## 4️⃣ Economic Impact Analysis

### Analysis Performed
- Order value growth comparison
- State-wise payment analysis
- Freight value analysis

### Key Finding
- Order cost increased by **136.97%** from Jan–Aug 2017 to Jan–Aug 2018

---

## 5️⃣ Delivery Time Analysis

### Analysis Performed
- Actual delivery duration calculation
- Delivery gap vs estimated date
- Fastest and slowest states by delivery performance

### Fastest Delivery States
- SP
- PR
- MG
- DF
- SC

### Slowest Delivery States
- RR
- AP
- AM
- AL
- PA

### Insight
Remote states experience significantly higher delivery times.

---

## 6️⃣ Payment Analysis

### Analysis Performed
- Payment type trend analysis
- Installment-based payment analysis

### Key Finding
- Single installment payments were most common with **49,057 orders**

---

# 💡 Key Insights

- Order volume grew by approximately **137%** from 2017 to 2018
- Afternoon is the peak order placement period
- SP state dominates customer and order volume
- Single-installment payments are most preferred
- Remote states face delivery delays
- Seasonal peaks were observed during August

---

# 📈 Business Impact

This project helped strengthen:
- SQL querying skills
- Data exploration techniques
- Business problem-solving
- Analytical thinking
- Real-world reporting skills

---

# 📁 Project Structure

```bash
sql-case-study/
│
├── queries/
│   ├── 01_data_exploration.sql
│   ├── 02_indepth_exploration.sql
│   ├── 03_ecommerce_evolution.sql
│   ├── 04_economy_analysis.sql
│   ├── 05_delivery_analysis.sql
│   └── 06_payment_analysis.sql
│
├── results/
│   ├── data_types.png
│   ├── time_range.png
│   └── ...
│
├── SQL_PROJECT.pdf
└── README.md
