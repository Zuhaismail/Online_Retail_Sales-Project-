# 🛍️ Online Retail Sales EDA & Dashboard

Welcome to the **Online Retail Sales EDA** project! This repository showcases an end-to-end analysis of real-world e-commerce data, covering data cleaning, in-depth exploratory data analysis (EDA), and insightful data visualization through Power BI.

## 📌 Project Objective

The goal of this project is to analyze customer purchasing behavior, identify top-performing products, discover seasonal sales trends, and segment customers based on buying habits. The project is designed to build a solid foundation in data analysis using **Pandas**, **Matplotlib**, **Seaborn**, and **Power BI**.

---

## 📁 Repository Contents

| File/Folder                     | Description                                                           |
| ------------------------------- | --------------------------------------------------------------------- |
| `Online_Retail_Sales_EDA.ipynb` | Python notebook with full data cleaning and exploratory data analysis |
| `Online_Retail_PowerBi.pbix`    | Interactive Power BI dashboard                                        |
| `cleaned_online_retail.zip`     | Cleaned dataset used for analysis                                     |
| `PowerBI_Dashboard_Images/`     | Screenshots of Power BI dashboard pages                               |
| `README.md`                     | Project overview and documentation                        |

---

## 📊 Dataset Overview

* Source: [Kaggle - Online Retail Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)
* Records: \~500,000 transactions
* Timeframe: December 2010 – December 2011

### Key Columns:

* `InvoiceNo`: Invoice number (transaction ID)
* `StockCode`: Product/item code
* `Description`: Product name
* `Quantity`: Number of products purchased
* `InvoiceDate`: Timestamp of purchase
* `UnitPrice`: Price per item
* `CustomerID`: Unique ID per customer
* `Country`: Customer’s country

---

## 🧹 Data Cleaning Steps

* Removed missing `CustomerID` and `Description` values
* Deleted duplicate rows
* Excluded canceled transactions (`InvoiceNo` starting with "C")
* Capped extreme outliers in `Quantity` and `UnitPrice`

---

## 📈 Exploratory Data Analysis

### 🔹 General Overview:

* Unique products
* Total transactions
* Unique customers
* Country-wise customer distribution

### 🔹 Product Analysis:

* Top 10 best-selling products
* Top revenue-generating products
* Products with invalid pricing

### 🔹 Customer Analysis:

* Highest purchasing customers
* Frequency distribution of purchases
* RFM segmentation for customer loyalty

### 🔹 Time Series Analysis:

* Monthly sales trends
* Weekly & daily purchase patterns
* Peak and low seasons

### 🔹 Country Insights:

* Orders and revenue by country

---

## 📊 Power BI Dashboard

**Interactive visualizations built in Power BI include:**

### 1. 📌 Sales Overview

* KPIs: Revenue, Total Invoices, Customer Count
* Monthly trend analysis

### 2. ⭐ Top Products

* Top 10 by Quantity and Revenue
* Product categories (Treemap / Pie Chart)

### 3. 👤 Customer Segmentation

* RFM (Recency, Frequency, Monetary) model
* Loyal customer identification

### 4. 🌍 Geographic Insights

* Sales distribution by country (Map and bar chart)

---

## 🚀 Tools & Libraries

* **Python**: Pandas, Matplotlib, Seaborn
* **Power BI**: Interactive dashboarding and reporting
* **Google Colab**: Online Python environment for data analysis


---

## 💡 Let's Connect!

If this project sparked your interest, feel free to explore the code, give it a ⭐! I'm always open to feedback, collaboration, or just a chat about data analytics and visualization.

