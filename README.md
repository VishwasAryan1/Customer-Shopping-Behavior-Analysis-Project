# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover customer purchasing patterns, identify revenue drivers, evaluate subscription behavior, and generate actionable business recommendations.

## Business Problem

Retail businesses generate large volumes of customer transaction data but often struggle to extract meaningful insights. This project aims to answer key business questions regarding customer spending, product performance, discounts, subscriptions, and customer loyalty.

---

## Dataset Information

- Records: 3,900
- Features: 18
- Customer Demographics
- Purchase Information
- Product Categories
- Subscription Status
- Review Ratings
- Discounts & Promotions
- Shipping Preferences

---

## Tech Stack

### Python
- Pandas

### SQL
- MySQL
- Window Functions
- CTEs
- Aggregations

### Business Intelligence
- Power BI

---

## Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning & Preprocessing
     ↓
Exploratory Data Analysis (Python)
     ↓
Feature Engineering
     ↓
SQL Business Analysis
     ↓
Power BI Dashboard
```

---

## Data Cleaning

- Handled missing review ratings using category-wise median imputation
- Standardized column names using snake_case
- Created customer age groups
- Generated purchase frequency features
- Removed redundant columns
- Performed data consistency validation

---

## SQL Business Analysis

### Revenue Analysis
- Revenue by Gender
- Revenue by Age Group

### Customer Analysis
- Customer Segmentation
- Repeat Buyers Analysis
- Subscriber vs Non-Subscriber Comparison

### Product Analysis
- Top Rated Products
- Top Products per Category
- Discount Dependent Products

### Operational Analysis
- Shipping Type Comparison
- Discount Usage Analysis

---

## Key Insights

- Male customers generated higher total revenue.
- Young adults contributed the highest revenue among age groups.
- Express shipping users showed higher average purchase values.
- Non-subscribers contributed the majority of overall revenue.
- Several products showed strong dependency on discounts.
- Most customers belonged to the loyal customer segment.

---

## Dashboard Features

- KPI Cards
- Revenue Analysis
- Customer Segmentation
- Subscription Analysis
- Category Performance
- Age Group Analysis
- Interactive Filters

---

## Business Recommendations

- Strengthen subscription benefits to improve adoption.
- Launch targeted loyalty programs.
- Optimize discount strategies.
- Promote top-rated products.
- Focus marketing efforts on high-value customer segments.

---

## Repository Structure

```text
Customer-Shopping-Behavior-Analysis
│
├── data
│   └── shopping_trends.csv
│
├── notebooks
│   └── customer_behavior_analysis.ipynb
│
├── sql
│   └── business_queries.sql
│
├── dashboard
│   └── customer_behavior_dashboard.pbix
│
├── images
│   └── dashboard.png
│
└── README.md
```

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- SQL Analytics
- Window Functions
- Customer Segmentation
- Business Intelligence
- Dashboard Development
- Data Storytelling

---

## Author

Vishwas Kumar

B.Tech, Metallurgical and Materials Engineering

National Institute of Technology Raipur
