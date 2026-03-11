# Retail Customer Behavior Analytics

## Project Description
This project analyzes customer shopping behavior using transactional data from **3,900 purchases across multiple product categories**. The objective is to identify patterns in customer demographics, purchasing habits, product performance, and subscription behavior to support data-driven business decisions.

The project demonstrates an **end-to-end data analytics workflow using Python for data cleaning, MySQL for analysis, and Power BI for visualization.**

---

## Dashboard Preview

![Retail Customer Behavior Dashboard](images/Dashboard.png)

The Power BI dashboard provides interactive insights including:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Customer Distribution by Subscription Status

Users can filter insights using:

- Gender  
- Subscription Status  
- Category  
- Shipping Type  

---

## Dataset Summary

- **Rows:** 3,900  
- **Columns:** 18  

### Key Features

**Customer Demographics**
- Age  
- Gender  
- Location  
- Subscription Status  

**Purchase Details**
- Item Purchased  
- Category  
- Purchase Amount  
- Season  
- Size  
- Color  

**Shopping Behavior**
- Discount Applied  
- Promo Code Used  
- Previous Purchases  
- Frequency of Purchases  
- Review Rating  
- Shipping Type  

---

## Project Workflow

### 1. Data Cleaning & Preparation (Python)

Libraries used:
- Pandas
- NumPy
- Matplotlib
- Seaborn

Steps performed:
- Loaded dataset using pandas
- Conducted initial exploration using `.info()` and `.describe()`
- Handled missing values in the **review_rating column**
- Standardized column names to **snake_case**
- Created new features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant column **promo_code_used**
- Loaded cleaned dataset into **MySQL database**

---

## Data Analysis Using MySQL

Key business analysis performed using SQL queries:

- Revenue comparison by gender
- Identification of high-spending discount users
- Top 5 products by average review rating
- Shipping type comparison (Standard vs Express)
- Subscribers vs non-subscribers spending behavior
- Discount-dependent products
- Customer segmentation (New, Returning, Loyal)
- Top products per category
- Subscription trends among repeat buyers
- Revenue contribution by age group

---

## Key Insights

- Male customers generated higher overall revenue.
- Non-subscribers contributed the majority of total revenue.
- Young adults generated the highest revenue among age groups.
- Express shipping users showed slightly higher purchase values.
- Some products rely heavily on discounts to drive sales.
- A large portion of customers fall into the loyal segment.

---

## Business Recommendations

- Promote subscription benefits to increase adoption.
- Implement loyalty programs for repeat buyers.
- Optimize discount strategies to maintain profit margins.
- Focus marketing on high-value customer segments.
- Promote top-rated products in campaigns.

---

## Tools & Technologies

- **Python** – Data cleaning and preprocessing  
- **MySQL** – Data analysis and querying  
- **Power BI** – Dashboard visualization  
- **Jupyter Notebook** – Exploratory data analysis  
