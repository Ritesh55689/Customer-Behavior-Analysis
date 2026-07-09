# Customer Shopping Behavior Analysis

An end-to-end Data Analytics project that analyzes customer shopping behavior using **Python**, **PostgreSQL**, and **Power BI**. The project focuses on cleaning raw customer transaction data, performing SQL-based business analysis, and creating an interactive dashboard to generate actionable business insights.

---

# Project Overview

This project analyzes customer shopping behavior using transactional data containing **3,900 customer purchases**.

The objective is to understand:

- Customer purchasing patterns
- Product performance
- Revenue trends
- Subscription behavior
- Customer segmentation
- Shopping preferences

The project follows the complete Data Analytics workflow:

Raw Data → Data Cleaning (Python) → SQL Analysis → Power BI Dashboard → Business Insights

---

# Tech Stack

- Python
- Pandas
- NumPy
- PostgreSQL
- SQL
- Power BI
- Jupyter Notebook

---

# Dataset

The dataset contains customer shopping information including:

- Customer Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Previous Purchases
- Purchase Frequency

Dataset Size:

- 3,900 Rows
- 18 Columns

---

# Data Cleaning (Python)

The dataset was cleaned using Python.

### Tasks Performed

- Loaded dataset using Pandas
- Checked data types
- Identified missing values
- Filled missing Review Ratings using category-wise median
- Converted column names to snake_case
- Created Age Group feature
- Created Purchase Frequency feature
- Removed redundant columns
- Exported cleaned data into PostgreSQL

---

# SQL Analysis

Business questions answered using PostgreSQL:

- Revenue by Gender
- High Spending Customers using Discounts
- Top 5 Highest Rated Products
- Shipping Type Comparison
- Subscribers vs Non-Subscribers Analysis
- Discount Dependent Products
- Customer Segmentation
- Top Products in Each Category
- Repeat Buyers Analysis
- Revenue by Age Group

---

# Power BI Dashboard

An interactive dashboard was built in Power BI containing:

- KPIs
- Revenue Analysis
- Customer Segmentation
- Product Category Analysis
- Subscription Analysis
- Shipping Analysis
- Purchase Trends
- Interactive Filters
- Charts and Visualizations

---

# Key Insights

- Subscribers generated higher overall revenue.
- Repeat customers contributed significantly to sales.
- Certain products relied heavily on discounts.
- Revenue varied across different age groups.
- Express shipping customers showed higher average purchase amounts.
- Top-rated products can be prioritized for marketing campaigns.

---

# Business Recommendations

- Increase subscription benefits.
- Introduce loyalty reward programs.
- Optimize discount strategies.
- Promote top-rated products.
- Focus marketing campaigns on high-value customer segments.

---
# Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- SQL Queries
- PostgreSQL
- Data Visualization
- Dashboard Design
- Business Analytics
- Data Storytelling
