# 🛒 Online Retail Data Analysis

An end-to-end data analysis project exploring customer behavior, product performance, and revenue trends using the Online Retail dataset. This project focuses on generating actionable business insights to improve sales, customer retention, and decision-making.

---

## 🎯 Business Objective

The objective of this project is to analyze transactional retail data to:

- Understand customer purchasing behavior  
- Identify high-performing products  
- Analyze revenue trends over time  
- Segment customers based on value (RFM analysis)  
- Generate actionable business recommendations  

---

## 📂 Dataset Description

The dataset contains transactional data from an online retail store, including:

- Invoice: Unique transaction ID  
- StockCode: Product code  
- Description: Product name  
- Quantity: Number of items purchased  
- InvoiceDate: Transaction date  
- Price: Price per unit  
- Customer ID: Unique customer identifier  
- Country: Customer location  

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 📊 Key Visualizations

### 📈 Monthly Revenue Trend
![Monthly Revenue](images/monthly_revenue.png)

**Insight:**
- Revenue shows strong seasonality with peaks towards the end of the year.
- This indicates higher demand during holiday periods.
- Business should prepare inventory and marketing strategies ahead of peak months.

---

### 🏆 Top Products by Revenue
![Top Products](images/top_products_revenue.png)

**Insight:**
- A small number of products generate the majority of revenue.
- This indicates strong product concentration.
- Business should focus on promoting and maintaining stock for these high-performing products.

---

### 🌍 Country-wise Revenue
![Country Revenue](images/country_revenue.png)

**Insight:**
- The majority of revenue comes from a single dominant country (UK).
- Other countries contribute significantly less.
- Business can explore expansion opportunities in underperforming regions.

---

### 📊 Customer Pareto Analysis
![Pareto](images/customer_pareto.png)

**Insight:**
- A small percentage of customers contribute a large portion of total revenue (80/20 rule).
- The business heavily depends on high-value customers.
- Retention strategies for top customers are critical for sustained revenue.

---

### 👥 RFM Customer Segmentation
![RFM](images/rfm_segments.png)

**Insight:**
- Customers are distributed across multiple segments, with a large portion being low-frequency buyers.
- High-value customers are limited but contribute significantly to revenue.
- Targeted marketing strategies can help convert low-value customers into loyal ones.