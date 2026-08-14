# 🍊 Swiggy Sales Analysis

## 📌 Project Overview

This project focuses on analyzing Swiggy sales and order data using Python to understand overall business performance, customer ratings, order behavior, and sales trends.

The analysis was performed using **Pandas, NumPy, Matplotlib, Seaborn, and Plotly**. The project includes data exploration, KPI calculation, trend analysis, food-category analysis, geographical analysis, quarterly performance analysis, and identification of top-performing cities.

The final analysis was designed around the business requirements and dashboard presented in the project presentation.

---

## 🎯 Business Objective

The objective of this project is to analyze Swiggy's sales data and identify important patterns in:

* Overall sales performance
* Customer ratings
* Average order value
* Number of orders
* Revenue contribution by food category
* State-wise sales performance
* Monthly, daily, and weekly sales trends
* Quarterly performance
* Top-performing cities

These insights can help understand sales behavior and identify areas of strong business performance.

---

## 📊 Key Performance Indicators (KPIs)

The project calculates the following major KPIs:

| KPI                     | Description                                |
| ----------------------- | ------------------------------------------ |
| **Total Sales**         | Overall revenue generated from food orders |
| **Average Rating**      | Average customer rating across restaurants |
| **Average Order Value** | Average revenue generated per order        |
| **Ratings Count**       | Total number of customer ratings/reviews   |
| **Total Orders**        | Total number of food orders                |

### KPI Results

* 💰 **Total Sales:** ₹53.01M
* ⭐ **Average Rating:** 4.34
* 🛒 **Average Order Value:** ₹268.51
* 👍 **Ratings Count:** 5.59M
* 📦 **Total Orders:** 197.K

---

## 🔍 Data Analysis Performed

### 1. Data Exploration

The dataset was explored using:

* `head()`
* `tail()`
* `shape`
* `info()`
* `dtypes`
* `describe()`

This helped understand the structure, dimensions, data types, and statistical characteristics of the dataset.

---

### 2. Monthly Sales Trend

Monthly revenue was calculated by extracting the month from the order date and grouping sales accordingly.

**Purpose:**
To understand how revenue changes over time and identify months with relatively high or low sales.

---

### 3. Daily Sales Trend

Sales were grouped according to the day of the week.

**Purpose:**
To compare revenue performance across Monday to Sunday and identify stronger sales days.

---

### 4. Sales by Food Category

The project classifies dishes into:

* **Veg**
* **Non-Veg**

The classification is based on keywords present in the dish name, including terms such as chicken, egg, fish, mutton, prawn, biryani, kabab, and non-veg.

Revenue was then compared between the two categories using a donut/pie chart.

---

### 5. State-wise Sales Analysis

Total revenue was grouped by state to understand the geographical distribution of sales.

A visualization was created to compare revenue generated across different states.

**Purpose:**
To identify states contributing strongly to overall revenue.

---

### 6. Quarterly Performance Analysis

The dataset was divided into quarters and analyzed using:

* Total Sales
* Total Orders
* Average Rating

The quarterly summary provides a combined view of business performance across different quarters.

---

### 7. Top 5 Cities by Sales

Cities were ranked according to their total sales.

The analysis identifies the **Top 5 cities contributing the highest revenue**.

According to the dashboard, Bengaluru is the leading city by sales, followed by Lucknow, Hyderabad, Mumbai, and New Delhi.

---

### 8. Weekly Sales Trend

Weekly revenue was calculated using the ISO week number from the order date.

A line chart was used to monitor weekly fluctuations in sales.

**Purpose:**
To identify sales consistency, fluctuations, and potential peak periods.

---

## 📈 Dashboard / Visualization Requirements

The project contains the following major visualizations:

* Monthly Sales Trend
* Daily Sales Trend
* Total Sales by Food Type
* Total Sales by State
* Quarterly Sales, Ratings & Orders
* Top 5 Cities by Sales
* Weekly Sales Trend

These chart requirements are directly aligned with the project's business requirements document in the presentation.

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly

### Development Environment

* Jupyter Notebook

### Dataset

* Excel (`swiggy_data.xlsx`)

---

## 📂 Project Structure

```text
Swiggy-Sales-Analysis/
│
├── Swiggy_Sales.ipynb
├── swiggy_data.xlsx
├── Swiggy PPT.pptx
└── README.md
```

> **Note:** If you do not want to upload the Excel dataset or PPT to GitHub, remove those files from the project structure above and mention the dataset source separately.

---

## 🔄 Project Workflow

```text
Raw Swiggy Data
       ↓
Data Import
       ↓
Data Exploration
       ↓
Data Cleaning & Preparation
       ↓
KPI Calculation
       ↓
Trend Analysis
       ↓
Category Analysis
       ↓
Geographical Analysis
       ↓
Quarterly Analysis
       ↓
City Ranking
       ↓
Visualization & Insights
```

---

## 💡 Key Insights

The analysis highlights several important business patterns:

* Swiggy generated approximately **₹53.01M in total sales** in the analyzed dataset.
* The average customer rating is **4.34**, indicating a relatively strong rating level.
* The average order value is approximately **₹268.51**.
* The dataset contains approximately **197.K orders**.
* **Non-Veg food contributes a larger share of revenue than Veg food** in the dashboard.
* **Bengaluru** is the highest-performing city among the Top 5 cities by sales.
* Sales vary across months, days, weeks, and states, allowing performance differences to be identified at multiple levels.

---

## 🚀 Skills Demonstrated

This project demonstrates practical skills in:

* Data Analysis with Python
* Pandas Data Manipulation
* NumPy
* Data Cleaning and Preparation
* KPI Development
* Exploratory Data Analysis (EDA)
* Time-Series Analysis
* GroupBy and Aggregation
* Data Visualization
* Plotly Interactive Visualization
* Business Requirement Analysis
* Business Insight Generation

---

## 📌 Conclusion

The Swiggy Sales Analysis project provides a comprehensive view of sales performance using Python-based data analysis and visualization techniques.

By combining KPIs with monthly, daily, weekly, quarterly, geographical, food-category, and city-level analysis, the project provides a structured approach to understanding revenue and order performance.

---

## 👨‍💻 Author

**Ankit Kumar**

**B.Tech – Metallurgical & Materials Engineering**
**NIT Jamshedpur**

---

⭐ If you find this project useful, consider giving the repository a star!
