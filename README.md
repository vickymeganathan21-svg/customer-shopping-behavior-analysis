# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data of **3,900 purchases** across multiple product categories.

The goal is to uncover:

* Customer spending patterns
* Product preferences
* Customer segments
* Subscription behavior

This helps businesses make **data-driven decisions**.

---

## 📊 Dataset Summary

* Rows: 3,900

* Columns: 18

* Features:

  * Customer demographics (Age, Gender, Location)
  * Purchase details (Category, Amount, Season)
  * Behavior (Discounts, Frequency, Ratings, Shipping)

* Missing Values:

  * 37 missing values in *Review Rating* column (handled using median)

---

## ⚙️ Tech Stack

* Python (Pandas, NumPy)
* PostgreSQL
* SQL
* Power BI

---

## 🔍 Data Analysis

### Python (Data Cleaning & Preparation)

* Handled missing values
* Feature engineering:

  * Age groups
  * Purchase frequency
* Column standardization
* Loaded data into PostgreSQL

---

### SQL Analysis

Performed business-driven queries:

1. Revenue by Gender
2. High-spending customers using discounts
3. Top-rated products
4. Shipping type comparison
5. Subscriber vs Non-subscriber analysis
6. Discount-dependent products
7. Customer segmentation
8. Top products per category
9. Repeat buyers & subscriptions
10. Revenue by age group

---

## 📈 Key Insights

* Male customers generated higher revenue
* Express shipping users spend slightly more
* Discounts drive purchases but not always higher revenue
* Loyal customers form the majority segment
* Young adults contribute highest revenue

---

## 📊 Dashboard

Interactive dashboard built using Power BI:

![Dashboard](images/dashboard.png)

---

## 💡 Business Recommendations

* Promote subscription benefits
* Introduce loyalty programs
* Optimize discount strategies
* Focus marketing on high-value age groups

---

## 🚀 How to Run

1. Clone the repo
2. Run Python notebook
3. Execute SQL queries in PostgreSQL
4. Open Power BI dashboard

---

## 📌 Author

**Vignesh M**
