## 📊 Customer Shopping Behavior Analysis

Python • PostgreSQL • Power BI

### 📌 Project Overview

This project is an end-to-end customer analytics solution that analyzes shopping behavior using Python for data cleaning & EDA, PostgreSQL for structured SQL analysis, and Power BI for interactive visualization.

The objective is to uncover customer spending patterns, product performance, discount dependency, and subscription behavior to support data-driven business decisions.

Dataset contains 3,900 real-world purchase records across multiple product categories.

### 🎯 Key Objectives

Understand customer purchasing behavior

Identify high-value customer segments

Analyze impact of discounts and subscriptions

Compare revenue across demographics

Deliver insights through an interactive dashboard

### 📂 Dataset Summary

Records: 3,900

Columns: 18

Data Type: Transactional retail data

### Key Features

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Amount, Season, Size, Color

Behavioral Data: Discounts, Purchase Frequency, Previous Purchases

Logistics: Shipping Type

Feedback: Review Rating

⚠️ Missing values were present in the Review Rating column and handled during preprocessing.

### 🛠 Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn)

PostgreSQL (SQL queries & segmentation)

Power BI (Dashboard & KPIs)

Jupyter Notebook

CSV → Database Pipeline

### 🔄 Data Cleaning & EDA (Python)

Performed using Python to ensure data quality before analysis.

Steps:

Loaded dataset using pandas

Inspected structure using .info() and .describe()

Handled missing values in review_rating using median imputation by category

Standardized column names to snake_case

Created engineered features:

age_group

purchase_frequency_days

Identified redundant columns (promo_code_used) and removed them

Validated consistency between discount-related fields

Loaded cleaned data into PostgreSQL database

This step ensures downstream SQL and BI analysis is reliable and scalable.

### 🗄 Database & SQL Analysis (PostgreSQL)

The cleaned dataset was stored in PostgreSQL for structured analysis.

Business Questions Answered:

Revenue contribution by gender

High-spending customers who still use discounts

Top 5 products by average rating

Purchase amount comparison by shipping type

Subscribers vs non-subscribers spending behavior

Products most dependent on discounts

Customer segmentation:

New

Returning

Loyal

Top 3 products in each category

Relationship between repeat purchases and subscription

Revenue distribution across age groups

SQL queries were optimized for clarity and business relevance.

### 📊 Power BI Dashboard

An interactive Power BI dashboard was built on top of the analyzed data.

Dashboard Highlights:

Total Revenue & Average Purchase KPIs

Customer Segmentation Overview

Revenue by Age Group & Gender

Discount vs Non-Discount Analysis

Subscription Impact on Spending

Product & Category Performance

Shipping Type Comparison

Includes slicers and filters for dynamic exploration.

### 🔍 Key Insights

Subscribers generate higher average revenue than non-subscribers

Loyal customers contribute a disproportionate share of revenue

Some products are highly discount-dependent, impacting margins

Express shipping customers tend to spend more per order

Certain age groups dominate overall revenue contribution

### 💡 Business Recommendations

Strengthen subscription programs with exclusive benefits

Invest in loyalty rewards to convert returning customers

Re-evaluate discount strategies for margin-heavy products

Prioritize top-rated products in marketing campaigns

Focus targeted marketing on high-revenue age groups

## 👤 Author

Akash
Aspiring Data Analyst     
Skills: Python | SQL | PostgreSQL | Power BI | Excel
