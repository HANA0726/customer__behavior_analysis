## 👨🏻‍💻 Customer Shopping Behavior Analysis
Customer Shopping Behavior Analysis Data analytics project exploring customer purchasing patterns using Python, PostgreSQL, and Power BI, with insights on customer segments, product performance, and revenue drivers.

---

## 📌 Project Overview

This project simulates a real-world data analytics workflow, taking raw retail data through every stage of the analytics pipeline — from cleaning and modeling to SQL querying, dashboard visualization, and a written business report.

The analysis answers key business questions:
- Which customer segments generate the most revenue?
- Which products have the highest ratings and the highest discount dependency?
- How do subscribers compare to non-subscribers in spending?
- Which age groups and shipping preferences drive the most value?

---

## 🗂️ Project Structure

```
customer-shopping-behavior-analysis/
│
├── Data_Cleaning.ipynb                            # Python EDA & data cleaning notebook
├── customer_behavior_sql_queries.sql              # SQL business queries (PostgreSQL)
├── Questions.txt                                  # Business questions answered via SQL
├── customer_behavior_dashboard.pbix               # Power BI interactive dashboard
├── customer_shopping_behavior.csv                 # Raw dataset
├── customer_shopping_behavior_report.pdf          # Full project report
├── Customer-Shopping-Behavior-presentation.pdf    # Project presentation deck
└── README.md
```

---

## 🔄 Project Workflow

### ✅ Step 1 — Data Preparation & EDA (Python)

### ✅ Step 2 — Data Analysis (SQL / PostgreSQL)
Ran 10 structured queries to answer real business questions

### ✅ Step 3 — Dashboard (Power BI)
Built an interactive dashboard to visualize KPIs and business trends 
### ✅ Step 4 — Report & Presentation
Wrote a professional project report summarizing methodology, key findings, data tables, and 6 strategic business recommendations. Also produced a presentation deck (`Customer-Shopping-Behavior-presentation.pdf`) to visually communicate insights to stakeholders.

---
## 📸 Dashboard Preview

Power BI interactive dashboard — filter by Gender, Category, Subscription Status, and Shipping Type.

---


## 📊 Key Findings

- 💰 **Male customers** generated ~2x more revenue than female customers ($157K vs $75K)
- 🔁 **79.9%** of customers are classified as **Loyal** (10+ purchases)
- 📦 **Express shipping** users spend slightly more on average ($60.48 vs $58.46)
- 🏷️ Products like **Hat** and **Sneakers** have ~50% discount rates — margin risk
- 🔔 Only **7.3%** of customers are subscribed — a major growth opportunity
- 🧑 **Young Adults** are the highest-revenue age group at $62,143

---

## 🛠️ How to Run This Project

**1. Clone the repository**
```bash
git clone https://github.com/HANA0726/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

**2. Run the Python notebook**
- Open `Data_Cleaning.ipynb`
- Install dependencies: `pip install pandas sqlalchemy psycopg2`
- Run all cells to clean the data and load it into PostgreSQL

**3. Run the SQL queries**
- Open `customer_behavior_sql_queries.sql` in pgAdmin or any PostgreSQL client
- The business questions are listed in `Questions.txt`
- Execute queries to explore business insights

**4. Open the Power BI dashboard**
- Open `customer_behavior_dashboard.pbix` in Power BI Desktop
- Connect to your local PostgreSQL database if prompted

---
 
## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| Python (pandas) | Data cleaning & feature engineering |
| PostgreSQL | SQL-based business analysis |
| Power BI | Interactive dashboard & visualization |
| Jupyter Notebook | EDA environment |

---
## 👨‍💻 About Me

I am a Data Science enthusiast focused on building end-to-end data projects and extracting actionable insights from data.

This project is part of my portfolio to demonstrate real-world analytics skills.

---

> ⭐ If you found this project useful, consider starring the repo — it helps others find it too!
