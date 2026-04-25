#  Sales Performance Dashboard (Google Sheets + Power BI)

## Overview

This project analyzes sales data to identify key trends, top-performing categories, regions, and products. The analysis was conducted using Google Sheets for data cleaning and Microsoft Power BI for interactive data visualization.

---

##  Problem Statement

Businesses need to understand their sales performance to make informed decisions.
This project answers:

* Which categories generate the most revenue?
* Which regions perform best or underperform?
* How do sales change over time?
* Which products contribute the most to overall sales?

---

##  Dataset

The dataset contains transactional sales data with the following key fields:

* `Order ID` – Unique identifier for each order
* `Order Date` – Date of transaction
* `Category` – Product category
* `Region` – Sales region
* `Product Name` – Product details
* `Sales` – Revenue generated

> Note: The dataset does not include cost or profit data; therefore, the analysis focuses solely on revenue (sales) performance.

---

## Tools & Technologies

* **Google Sheets** – Data cleaning and preparation
* **Microsoft Power BI** – Data visualization and dashboard creation

---

##  Data Cleaning (Google Sheets)

The dataset was prepared using Google Sheets:

* Removed duplicate records
* Identified and handled blank/missing values
* Verified correct data formats (dates and numeric values)
* Ensured Sales column remained numeric for analysis and formatted as currency for presentation

---

##  Dashboard Development (Power BI)

An interactive dashboard was created in Power BI featuring:

### 🔹 Key Metrics (KPIs)

* Total Sales
* Total Orders

### 🔹 Visualizations

* Sales by Category
* Sales by Region
* Monthly Sales Trend
* Top 10 Products by Sales

### 🔹 Interactivity

* Filters (slicers) for:

  * Region
  * Category
  * Date

---

##  Key Insights

* Certain product categories generate significantly higher revenue than others
* Sales performance varies across regions, with some regions underperforming
* Sales trends show fluctuations over time, indicating possible seasonality
* A small number of products contribute a large portion of total revenue

---

##  Business Recommendations

* Focus marketing efforts on high-performing categories
* Investigate and improve underperforming regions
* Promote top-selling products to maximize revenue
* Use sales trends to plan inventory and marketing campaigns

---

##  Project Structure

```
sales-performance-dashboard/
│── dataset.csv
│── cleaned_sales_data.csv
│── sales_dashboard.pbix
│── README.md
```

---

##  Conclusion

This project demonstrates how sales data can be transformed into actionable insights using data cleaning and visualization tools. The dashboard enables stakeholders to explore performance dynamically and make informed business decisions.

---

##  Author

**Emmanuel Harrison Pratt**
Aspiring Data Analyst | SQL | Excel | Power BI | Data-Driven Insights
