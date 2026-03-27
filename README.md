# 📊 Sales Data Analysis using SQL, Python & Visualization

## 📌 Project Overview

This project analyzes sales data using SQL and Python to uncover insights related to revenue, product performance, customer behavior, and regional sales trends. The analysis combines structured querying with data visualization to provide a complete analytical workflow.

---

## 🎯 Objectives

* Analyze total revenue and sales distribution
* Identify top-performing products and categories
* Study customer segmentation and behavior
* Explore regional sales performance
* Visualize trends and patterns using charts

---

## 🛠️ Tools & Technologies

* SQL (SQLite)
* Python (Pandas, NumPy)
* Matplotlib & Seaborn
* Jupyter Notebook

---

## 📊 Dataset Description

The dataset contains 9,800 sales records with features such as:

* Order and shipping details
* Customer segments
* Product categories and sub-categories
* Geographic information
* Sales values

---

## 🔍 Analysis Performed

### 1. Data Cleaning & Preparation

* Checked missing values
* Verified data types
* Prepared dataset for analysis

### 2. SQL Analysis

* Overall sales summary
* Sales by category
* Sales by region
* Top-performing products
* Sales by customer segment

### 3. Python Analysis

* Data manipulation using Pandas
* Statistical summary
* Data validation

### 4. Data Visualization

* Sales by category (bar chart)
* Sales by region (bar chart)
* Sales trends (line chart)
* Segment distribution (pie chart)
* Correlation heatmap

---

## 🔥 Key Insights

* Technology category generates the highest revenue
* Office Supplies have the highest number of transactions
* West and East regions lead in total sales
* A small number of products contribute significantly to revenue
* Customer segments show different spending behaviors

---

## 📊 Sample SQL Query

```sql
SELECT Category, SUM(Sales) AS Total_Sales
FROM sales
GROUP BY Category;
```

---

## 📈 Visualizations

The project includes multiple charts to better understand sales distribution, trends, and relationships between variables.

---

## 📊 Conclusion

The analysis shows that revenue is driven by a combination of product category, customer segment, and regional performance. High-value products and key regions play a critical role in overall business success.

---

## ⚠️ Limitations

* Missing values in Postal Code column
* No profit/cost data available
* Limited customer demographic information
* External factors not included

---

## 🚀 Future Improvements

* Add profit analysis
* Build interactive dashboards (Power BI / Tableau)
* Apply predictive modeling for sales forecasting

---

## 📁 Project Structure

* `Sales_SQL_Python_Analysis.ipynb` → Main notebook
* `dataset.csv` → Dataset

**Usman Haider**
BS Data Science Student | Aspiring Data Analyst
