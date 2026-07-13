# 🛍️ Customer Behavior Data Analyst Project

---

An end-to-end data analytics project that explores customer shopping behavior using **Python, SQL, and Power BI** to uncover trends in spending, discounts, subscriptions, and product preferences, helping a retail business make smarter, data-driven decisions.

## 🧰 Tech Stack

- 🐍 Python (Pandas)
- 🗃️ PostgreSQL
- 📊 Power BI
- 🎨 Gamma AI

---

# 📌 Project Overview

The goal of this project is to simulate a **corporate-grade end-to-end data analytics workflow**, demonstrating the ability to translate raw data into strategic business intelligence by:

✅ **Data Preparation, Modeling & Exploratory Data Analysis (Python)**  
Clean and transform the raw dataset for analysis.

✅ **Data Analysis (SQL)**  
Simulate business transactions and run queries to extract insights on customer segments, loyalty, and purchase drivers.

✅ **Visualization & Insights (Power BI)**  
Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.

✅ **Report & Presentation**  
Write a clear project report summarizing key findings and business recommendations. Prepare a presentation that visually communicates insights and actionable recommendations to stakeholders.

---

# 📑 Table of Contents

- 🎯 Business Problem
- 🔄 Project Workflow
- 📌 Workflow Diagram
- 📊 Dataset Overview
- 📁 Project Structure
- 🐍 Data Preparation & EDA (Python)
- 🗃️ Data Analysis (SQL)
- 📈 Dashboard (Power BI)
- 💡 Business Recommendations
- 👥 Team

---

# 🎯 Business Problem

A leading retail company wants to better understand its customers' shopping behavior to improve sales, customer satisfaction, and long-term loyalty.

Management has noticed shifts in purchasing patterns across demographics, product categories, and sales channels and wants to identify which factors—discounts, reviews, seasons, or payment preferences—drive customer decisions and repeat purchases.

### Overarching Business Question

> **How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?**

---

# 🔄 Project Workflow

1. 📑 Business Problem Statement
2. 🐍 Data Modelling & EDA in Python (Import raw data into Python)
3. 🗃️ Data Analysis in SQL (Load cleaned data into PostgreSQL)
4. 📊 Interactive Dashboard in Power BI (Connect SQL Database to Power BI)
5. 📄 Project Report (Summarize findings)
6. 🎤 Presentation using Gamma AI (Present to stakeholders)
7. 🐙 GitHub Repository (Upload all project files)

---

![image alt](https://github.com/Krishpatel369/customer_behavior_analysis/blob/aa595a9613f79477660b181f8805480f40d04b1c/step%20to%20create%20a%20project.png)

---

# 📊 Dataset Overview

| Attribute | Detail |
|-----------|--------|
| Total Records | 3,900 purchase transactions |
| Total Columns | 18 |
| Missing Values | 97 in `review_rating` |
| Key Features | Age, Gender, Location, Subscription Status, Item Purchased, Category, Purchase Amount, Season, Size, Color, Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type |

---

# 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── dashboard/
│   └── customer_behavior_dashboard.pbix
│
├── report/
│   └── Customer_Shopping_Behavior_Analysis.pdf
│
├── presentation/
│   └── Customer-Shopping-Behavior-Analysis.pptx
│
└── README.md
```

---

# 🐍 Data Preparation & EDA (Python)

### Key Steps Performed

- 📥 **Data Loading**  
  Imported the dataset using Pandas.

- 🔍 **Initial Exploration**  
  Used `df.info()` and `df.describe()` to understand structure and summary statistics.

- 🧹 **Missing Data Handling**  
  Imputed missing `review_rating` values using the median rating per product category.

- 📝 **Column Standardization**  
  Renamed all columns to `snake_case`.

- ⚙️ **Feature Engineering**
  - Created `age_group` by binning customer ages.
  - Created `purchase_frequency_days` from purchase frequency data.

- ✅ **Data Consistency**
  - Verified redundancy between `discount_applied` and `promo_code_used`.
  - Dropped `promo_code_used`.

- 🗄️ **Database Integration**
  Connected the cleaned DataFrame to PostgreSQL for SQL-based analysis.

---

# 🗃️ Data Analysis (SQL) – Key Insights

| # | Business Question | Key Insight |
|---|-------------------|-------------|
| 1 | Revenue by Gender | Male customers generated **315,789** vs Female **375,191** in total revenue. |
| 2 | High-Spending Discount Users | **839 customers** used discounts while spending above the average purchase amount. |
| 3 | Top 5 Products by Rating | Gloves (3.86), Sandals (3.84), Boots (3.82), Hat (3.80), Skirt (3.78) |
| 4 | Standard vs Express Shipping | Express shipping (**360.48**) slightly outperformed Standard (**358.46**) in average purchase value. |
| 5 | Subscribers vs Non-Subscribers | Non-subscribers generated more revenue (**170,436**) than subscribers (**62,645**), while average spending remained similar. |
| 6 | Discount-Dependent Products | Hat (50%), Sneakers (49.66%), Coat (49.07%), Sweater (48.17%), Pants (47.37%). |
| 7 | Customer Segmentation | Loyal: **3,116** • Returning: **701** • New: **83** |
| 8 | Top 3 Products per Category | Clothing: Blouse, Pants, Shirt • Footwear: Sandals, Shoes, Sneakers |
| 9 | Repeat Buyers & Subscriptions | Repeat purchasing does not strongly predict subscription status. |
| 10 | Revenue by Age Group | Young Adults generated the highest revenue. |

> All SQL queries are available in **sql/customer_behavior_sql_queries.sql**

---

# 📈 Dashboard (Power BI)

### Dashboard KPIs

- 👥 **3.9K Total Customers**
- 💰 **$59.76 Average Purchase Amount**
- ⭐ **3.75 Average Review Rating**

### Dashboard Includes

- 🍩 Subscription Split
- 📊 Revenue by Category
- 📈 Revenue by Age Group
- 💵 Sales by Category
- 🎚️ Slicers for
  - Gender
  - Category
  - Shipping Type
  - Subscription Status

**Dashboard File**

```
dashboard/customer_behavior_dashboard.pbix
```

---

# 💡 Business Recommendations

- 🎁 **Boost Subscriptions**  
  Promote exclusive benefits to convert non-subscribers into subscribers.

- 🏆 **Customer Loyalty Programs**  
  Reward repeat buyers to strengthen long-term retention.

- 🏷️ **Review Discount Policy**  
  Balance promotional discounts with long-term profitability.

- 🌟 **Product Positioning**  
  Highlight top-rated and best-selling products in campaigns.

- 🎯 **Targeted Marketing**  
  Focus marketing efforts on Young Adults and Express Shipping users.

---

# 👥 Team

This project was completed as a **Final Year College Project** at **Dr. Subhash University**.

| Role | Name |
|------|------|
| 🧑‍💼 Team Leader | Ghodasara Krish |
| 👨‍💻 Team Member | Parmar Harsh |
| 👩‍💻 Team Member | Ribadiya Nensi |
| 🎓 Guide | Professor Vijay Manavar |

---
