Customer Behavior Data Analyst Project
----------------------------------------------------------------------------------------------------------------------------------------------------------------
An end-to-end data analytics project that explores customer shopping behavior using 
Python, SQL, and Power BI to uncover trends in spending, discounts, subscriptions,
and product preferences helping a retail business make smarter, data-driven decisions.
🧰Tech Stack: Python (Pandas) PostgreSQL Power BI Gamma AI
----------------------------------------------------------------------------------------------------------------------------------------------------------------
📌Project Overview

The goal of this project is to simulate a corporate-grade end-to-end data analytics
workflow, demonstrating the ability to translate raw data into strategic business 
intelligence by:

✅Data Preparation, Modeling & Exploratory Data Analysis (Python)  Clean and transform 
the raw dataset for analysis.

✅Data Analysis (SQL)  Simulate business transactions, and run queries to extract insights 
on customer segments, loyalty, and purchase drivers.

✅Visualization & Insights (Power BI)  Build an interactive dashboard that highlights hey
patterns and trends, enabling stakeholders to make data-driven decisions.

✅Report and Presentation  Write a clear project report summarizing key findings and business
recommendations. Prepare a presentation that visually communicates insights and actionable 
recommendations to stakeholders.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
📑Table of Contents

🎯Business Problem
🔄Project Workflow
📊Dataset Overview
📁Project Structure
🐍Data Preparation & EDA (Python)
🗃️Data Analysis (SQL)  Hey Insights
📈 Dashboard (Power BI)
💡Business Recommendations
👥Team
----------------------------------------------------------------------------------------------------------------------------------------------------------------
🎯Business Problem
A leading retail company wants to better understand its customers' shopping behavior to 
improve sales, customer satisfaction, and long-term loyalty. Management has noticed shifts 
in purchasing patterns across demographics, product categories, and sales channels, and wants
to know which factors  discounts, reviews, seasons, or payment preferences  drive customer 
decisions and repeat purchases.

Overarching Business Question:- How can the company leverage consumer shopping data to
identify trends, improve customer engagement, and optimize marketing and product strategies?
----------------------------------------------------------------------------------------------------------------------------------------------------------------
🔄Project Workflow
1.📑Business Problem Statement
2.🐍Data Modelling & EDA in Python (import raw data into Python)
3.🗃️Data Analysis in SQL (load cleaned data into a SQL database)
4.📊Interactive Dashboard in Power BI (connect SQL database to Power BI)
5.📄Project Report (summarize findings)
6.🎤Presentation using Gamma AI (present to stakeholders)
7.🐙GitHub Repository (upload all project files)
----------------------------------------------------------------------------------------------------------------------------------------------------------------
📊Dataset Overview
Attribute	           Detail

Total Records       3,900 purchase transactions

Total Columns       18

Missing Valuse      97 in review_rating 

Key Features        Age, Gender, Location, Subscription Status, 
 										Item Purchased, Category, Purchase Amount, 
										Season, Size, Color, Discount Applied,	
										Promo Code Used, Previous Purchases, 
										Frequency of Purchases, Review Rating,
										Shipping Type

----------------------------------------------------------------------------------------------------------------------------------------------------------------
📁Project Structure

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
----------------------------------------------------------------------------------------------------------------------------------------------------------------
📄Data Preparation & EDA (Python)
Key steps performed before analysis:

Data Loading:- Imported the dataset using pandas.

Initial Exploration:- Used df.info() and .describe() to understand structure and summary statistics.

Missing Data Handling:- Imputed missing review_rating values using the median rating per product category.

Column Standardization:- Renamed all columns to snake_case for consistency.

Feature Engineering:-
				Created age_group by binning customer ages.
				Created purchase_frequency_days from purchase frequency data.

Data Consistency:- CheckVerified redundancy between discount_applied and promo_code_used; dropped promo_code_used.

Database Integration:- Connected the cleaned DataFrame to PostgreSQL for SQL-based analysis.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
🗃️Data Analysis (SQL)  Hey Insights

#	Business Question														Hey Insight

1	Revenue by gender														Male customers generated 3157,890 vs Female 375,191 in total revenue
2	High-spending	discount users								839 customers used discounts yet spent above the average purchase amount
3	Top 5products by rating											Gloves (3.86), Sandals (3.84), Boots (3.82), Hat (3.80), Skirt (3.78)	
4	Standard vs Express	Express shipping				(360.48 avg) slightly outspends Standard (358.46 avg)
5	Subscribers vs non-subscribers							Non-subscribers drive far more total revenue ( 170,436 vs 62,645), though avg. spend is similar (-659.5-359.9)
6	Discount-dependent products							  	Hat (50%), Sneakers (49.66%), Coat (49.07%), Sweater (48.17%),Pants (47.37%) rely most on discounts
7	Customer segmentation												Loyal: 3,116 Returnin-g: 701 New: 83
8	Top 3products per	category									E.g., Clothing	Blouse, Pants, Shirt - Footwear	Sandals, Shoes,Sneakers
9	Repeat buyers & subscriptions								Of repeat buyers, 958 subscribe vs 2,518 who don't  repeat purchasing doesn't strongly predict subscription
10	Revenue by age group											Young Adult (662,143) > Middle-aged (359,197) > Adult (655,978) > Senior ( 55,763)

All queries are available in	sql/customer_behavior_sql_queries.sql
----------------------------------------------------------------------------------------------------------------------------------------------------------------
📈 Dashboard (Power BI)

👥 3.9K Total Customers
💰 $59.76 Average Purchase Amount
⭐ 3.75 Average Review Rating
🍩 Subscription split, Revenue & Sales by Category, Revenue & Sales by Age Group
🎚️ Slicers for Gender, Category, Shipping Type, and Subscription Status

Dashboard file: dashboard/customer_behavior_dashboard.pbix
----------------------------------------------------------------------------------------------------------------------------------------------------------------
💡 Business Recommendations

🎁 Boost Subscriptions Promote exclusive benefits to convert non-subscribers, who currently drive the majority of revenue.
🏆 Customer Loyalty Programs Reward repeat buyers to move them into the "Loyal" segment.
🏷️ Review Discount Policy — Balance short-term sales boosts against long-term margin control.
🌟 Product Positioning — Feature top-rated and best-selling products more prominently in campaigns.
🎯 Targeted Marketing — Focus efforts on high-revenue age groups (Young Adults) and Express-shipping users.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
👥 Team

This project was completed as a Final Year College Project at Dr. Subhash University.

Role											Name

🧑‍💼 Team Leader					Ghodasara Krish
👨‍💻 Team Member						Parmar Harsh 
👩‍💻 Team Member						Ribadiya Nensi
🎓 Guide									Professor Vijay Manavar
