# Global-Sales-Dashboard-PowerBI
Interactive Power BI dashboard for global sales analysis featuring KPI tracking, sales trends, category performance, customer insights, geographic analysis, and product profitability using DAX measures and interactive visualizations.

# 🌍 Global Sales Dashboard | Power BI

## 📌 Project Overview

The Global Sales Dashboard is an interactive Business Intelligence solution built using Power BI to analyze worldwide sales performance across countries, categories, products, and customers.

This dashboard provides key business insights through KPI tracking, sales trends, customer analysis, product performance, geographic analysis, and profitability metrics, helping stakeholders make data-driven decisions.

---

## 📊 Dashboard Preview

![Global Sales Dashboard](images/Global%20Sales%20Dashboard.png)

## 🎯 Objectives

- Monitor overall business performance.
- Analyze sales and profit trends over time.
- Identify top-performing products and customers.
- Evaluate category-wise sales contribution.
- Visualize country-wise sales distribution.
- Discover profitable and loss-making products.
- Enable interactive filtering for detailed analysis.

---

## 📈 Key Performance Indicators (KPIs)

| KPI | Value |
|------|--------|
| Total Sales | ₹12.64M |
| Total Profit | ₹1.47M |
| Total Orders | 26K |
| Total Customers | 17K |
| Total Quantity Sold | 178K |

---

## 📌 Dashboard Features

### Executive Summary
- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Total Quantity

### Sales Trend Analysis
- Monthly Sales Trend
- Year-wise Performance Tracking

### Category Analysis
- Technology
- Furniture
- Office Supplies

### Geographic Analysis
- Country-wise Sales Distribution
- Global Market Insights

### Customer Analysis
- Top 10 Customers by Sales
- Customer Revenue Contribution

### Product Analysis
- Top Selling Products
- Product Performance Ranking

### Profitability Analysis
- Sales vs Profit Scatter Chart
- Category-wise Product Performance

### Interactive Filters
- Year
- Market
- Region
- Country
- Category
- Segment

---

## 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Interactive Visualizations

---

## 📂 Dataset Information

The dataset contains:

- Orders Data
- Customer Information
- Product Information
- Geographic Data
- Sales Metrics
- Profit Metrics
- Quantity Metrics

Total Records: **51,000+**

---

## 📐 DAX Measures Used

```DAX
Total Sales =
SUM(Orders[Sales])

Total Profit =
SUM(Orders[Profit])

Total Orders =
DISTINCTCOUNT(Orders[Order ID])

Total Customers =
DISTINCTCOUNT(Orders[Customer ID])

Total Quantity =
SUM(Orders[Quantity])
