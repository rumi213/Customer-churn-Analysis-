# 🛒 Customer Churn Analysis for E-Commerce

## 📌 Project Overview

Customer retention is a key challenge in the e-commerce industry. Understanding why customers stop purchasing helps businesses improve customer satisfaction, increase repeat purchases, and maximize revenue.

This project analyzes over **100,000 customer orders** from the **Olist Brazilian E-Commerce Platform** to identify factors contributing to customer churn. Using **Advanced SQL**, **Python**, and **Data Visualization**, customer behavior patterns were explored and transformed into actionable business insights.

---

## 🎯 Objective

The primary objective of this project was to:

* Analyze customer purchasing behavior
* Identify indicators of customer churn
* Build customer-level metrics using RFM analysis
* Discover relationships between delivery performance and customer retention
* Provide data-driven recommendations to improve customer loyalty

---

## 📊 Dataset

The project uses the **Brazilian E-Commerce Public Dataset by Olist**, which contains:

* 100K+ orders
* Customer information
* Order details
* Payment records
* Product information
* Customer reviews
* Delivery and logistics data

The dataset provides a complete view of the customer journey from purchase to delivery and feedback.

---

## 🛠️ Tools & Technologies

### Languages

* Python
* SQL

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Database Concepts

* Joins
* Common Table Expressions (CTEs)
* Window Functions
* Aggregations
* Subqueries

---

## 🔍 Project Workflow

### 1. Data Preparation

* Imported and cleaned multiple datasets
* Handled missing values and inconsistencies
* Merged tables to create a unified customer view

### 2. Analytics Base Table (ABT) Creation

Built a customer-level Analytics Base Table using Advanced SQL.

Key metrics generated:

#### Recency

Days since the customer's last purchase.

#### Frequency

Total number of orders placed by a customer.

#### Monetary Value

Total amount spent by a customer.

These RFM metrics were calculated using SQL aggregations and window functions to enable customer segmentation and churn analysis.

### 3. Exploratory Data Analysis (EDA)

Performed detailed exploratory analysis to understand:

* Customer purchasing patterns
* Revenue distribution
* Order frequency trends
* Delivery performance
* Customer satisfaction trends

### 4. Churn Driver Analysis

Investigated factors contributing to customer attrition, including:

* Delivery delays
* Freight charges
* Purchase frequency
* Customer review scores
* Order value patterns

---

## 📈 Key Findings

### 🚚 Delivery Delays Increase Churn Risk

Customers experiencing delayed deliveries showed a significantly higher likelihood of discontinuing future purchases.

### ⭐ Customer Satisfaction Drives Retention

Lower review scores were associated with reduced customer retention and repeat purchases.

### 💰 High-Value Customers Show Different Purchase Patterns

Customers with higher monetary value demonstrated stronger engagement and lower churn tendencies.

### 🔄 Purchase Frequency Matters

Customers with longer inactivity periods and fewer purchases were more likely to churn.

---

## 📊 Business Impact

The analysis provided actionable recommendations that can help e-commerce businesses:

* Improve delivery performance
* Enhance customer experience
* Prioritize high-value customer retention strategies
* Develop targeted marketing campaigns
* Reduce customer churn through proactive intervention

---

## 📂 Project Structure

```text
Customer-Churn-Analysis/
│
├── Customer_Churn_Analysis.ipynb
├── create_analytics_table.sql
├── Master_table.csv
├── README.md
│
├── data/
├── sql/
└── visualizations/
```

---

## 🚀 conclusion

Successfully analyzed over **100,000+ order records**, created an **Analytics Base Table (ABT)** using advanced SQL techniques, and identified critical churn indicators through exploratory data analysis.

The findings highlight the importance of delivery efficiency, customer satisfaction, and purchasing behavior in driving customer retention.

