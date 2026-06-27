<img width="1920" height="1024" alt="main dashboard" src="https://github.com/user-attachments/assets/03025592-0275-4ab9-954b-e25bca7e98a3" />
---
## 📊 ShopSphere Retail Analytics Dashboard

A comprehensive **Power BI Business Intelligence Dashboard** built using a retail sales dataset containing approximately **120,000 transactions (2022–2024)**. This project transforms raw sales data into interactive dashboards that provide actionable business insights for executives and decision-makers.

---

## 📖 Project Overview

The ShopSphere Retail Analytics Dashboard was developed to analyze retail sales performance, profitability, customer behavior, and regional trends through interactive visualizations.

The solution uses **Power Query** for data preparation, **Star Schema** data modeling, and **DAX** measures to deliver dynamic business insights.

---

## 🎯 Project Objectives

* Analyze overall sales performance
* Measure profitability and margins
* Track Year-to-Date (YTD) and Year-over-Year (YoY) sales
* Evaluate product and category performance
* Understand customer purchasing behavior
* Monitor return rates
* Enable interactive filtering for business users

---

## 🛠️ Tools & Technologies

* Microsoft Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* CSV Files
* Star Schema Data Modeling

---

## 📂 Dataset

The project uses six CSV files organized in a star schema.

### Fact Tables

* fact_sales
* fact_returns

### Dimension Tables

* dim_products
* dim_customers
* dim_stores
* dim_date (Created in Power BI)

---

## 📊 Dashboard Pages

### 📈 Executive Overview

Provides a high-level summary of business performance.

**Key Features**

* Total Sales
* Gross Profit
* Profit Margin %
* Average Order Value (AOV)
* Return Rate %
* Sales Trend Analysis
* Sales by Category
* Regional Sales Performance
* Interactive Slicers

---

### 📦 Product & Profitability

Analyzes product performance and profitability.

**Key Features**

* Top Selling Products
* Most Profitable Products
* Profit by Category
* Brand Performance
* Product Return Analysis

---

### 👥 Customer Insights

Provides customer-focused analytics.

**Key Features**

* Active Customers
* Returning Customers
* Customer Segmentation
* Regional Customer Distribution
* Customer Purchase Trends

---

## 📐 Data Model

The project follows a **Star Schema** consisting of:

* Sales Fact Table
* Returns Fact Table
* Product Dimension
* Customer Dimension
* Store Dimension
* Date Dimension

---

## 📊 DAX Measures

The dashboard includes custom measures such as:

* Total Sales
* Total Orders
* Total Quantity Sold
* Total COGS
* Gross Profit
* Profit Margin %
* Average Order Value (AOV)
* Total Returns
* Return Rate %
* Active Customers
* Sales YTD
* Sales Previous Year
* YoY Growth %

---

## 📸 Dashboard Preview

### Executive Overview

> *(<img width="1920" height="1024" alt="main dashboard" src="https://github.com/user-attachments/assets/bff2ac69-ced2-4439-a4e3-1b6e46a7b63c" />
)*

### Product & Profitability

> *(<img width="1920" height="1024" alt="product   profitability" src="https://github.com/user-attachments/assets/c67f81c7-86f6-412d-9a1d-2353b779420f" />
)*

### Customer Insights

> *(<img width="1920" height="1035" alt="customer insights" src="https://github.com/user-attachments/assets/00b950f9-c141-4764-9da5-0d8128a51f6d" />
)*

### Data Model

> *(<img width="1920" height="1080" alt="Data model" src="https://github.com/user-attachments/assets/0ad768f7-f38d-48f3-834c-6656d8a780ea" />
)*

---

## 💡 Business Insights

The dashboard enables stakeholders to:

* Monitor sales performance across multiple years.
* Identify high-performing product categories.
* Compare current sales with previous years.
* Measure profitability and margins.
* Evaluate regional business performance.
* Analyze customer purchasing behavior.
* Track return rates for operational improvement.

---

## 📁 Repository Structure

```text
ShopSphere-Analytics/
│
├── Data/
│   ├── fact_sales.csv
│   ├── fact_returns.csv
│   ├── dim_products.csv
│   ├── dim_customers.csv
│   ├── dim_stores.csv
│
├── Insights/
│   └── ShopSphere_Insights.pdf
│
├── Screenshots/
│   ├── Executive_Overview.png
│   ├── Product_Profitability.png
│   ├── Customer_Insights.png
│   └── Data_Model.png
│
├── ShopSphere_Analytics_Nahla.pbix
│
└── README.md
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `ShopSphere_Analytics_Nahla.pbix` using Microsoft Power BI Desktop.
3. If prompted, reconnect the dataset from the **Data** folder.
4. Refresh the data model.
5. Explore the interactive dashboards using the slicers.

---

## 👩‍💻 Author

**Fathima Nahla Noushad**

Aspiring Data Analyst | Power BI | SQL | Python

---


