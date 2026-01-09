# # 🛒 E-Commerce Sales Analysis Dashboard (Power BI)

## 📌 Project Overview
This project is part of **Task 1** of the **Data Science & Analytics Internship at Future Interns**.  
The objective of this task is to analyze real-world **e-commerce sales data** and build an **interactive Power BI dashboard** that helps business stakeholders understand sales performance, customer behavior, and revenue trends.

The dashboard is designed to answer key business questions such as:
- What are the **best-selling products**?
- **When do sales peak** during the year?
- Which **countries and categories** contribute the most revenue?
- How do **customers and order volumes** change over time?

---

## 📊 Dashboard Highlights
The Power BI dashboard includes:

- **KPIs**
  - Total Revenue
  - Total Quantity Sold
  - Total Orders
  - Total Customers

- **Visual Insights**
  - 📈 Monthly revenue trends
  - 🛍️ Top-selling products by quantity
  - 🌍 Country-wise sales distribution
  - 📅 Year-wise analysis (2010 & 2011)
  - 🎯 Interactive filters for better exploration

---

## 🗂️ Dataset Information
Link: https://www.kaggle.com/datasets/mathchi/online-retail-ii-data-set-from-ml-repository
#### 🧾 Description
This dataset contains transactions of a **UK-based online retail company** selling gift items between:
- **01 December 2009 – 09 December 2011**

The dataset includes both retail and wholesale customers.

| Column Name   | Description |
|--------------|------------|
| InvoiceNo    | Unique invoice number (starting with 'C' indicates cancellation) |
| StockCode    | Unique product code |
| Description  | Product name |
| Quantity     | Quantity of items per transaction |
| InvoiceDate  | Date and time of transaction |
| UnitPrice   | Price per unit (£) |
| CustomerID  | Unique customer identifier |
| Country     | Customer’s country |

---

## 🔧 Tools & Technologies Used
- **Power BI Desktop** – Data modeling, DAX, and dashboard creation
- **Microsoft Excel** – Initial data exploration and cleaning
- **DAX (Data Analysis Expressions)** – Creating calculated measures & KPIs

---

## 🧹 Data Cleaning & Transformation
The following preprocessing steps were performed:
- Removed null and invalid values
- Handled cancelled transactions
- Created **Year** and **Month** columns from InvoiceDate
- Generated calculated measures such as:
  - Total Revenue
  - Total Orders
  - Total Customers
- Standardized country and product descriptions

---

## 🎯 Skills Gained
- 💡 Data cleaning & transformation
- 📆 Time-series analysis
- 📊 DAX for KPI creation
- 📈 Business storytelling with visuals
- 📥 Importing and handling Excel/CSV datasets
- 🧠 Analytical thinking for business use-cases

---

## 📌 Key Insights
- Sales peak during specific months i.e. during November and December, showing strong seasonality
- A small number of products contribute to a large portion of total sales
- The **United Kingdom** is the dominant revenue-generating country
- Revenue and order volumes show noticeable variation across years

---
## 📚 References & Acknowledgements
- UCI ML Repository – Online Retail II Dataset
- Future Interns – Data Science & Analytics Internship Program

---

## 👤 Author
**Tekendra Joshi**  
Data Science & Analytics Intern – Future Interns  
