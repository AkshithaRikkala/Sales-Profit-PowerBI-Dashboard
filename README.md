# 📊 Sales & Profit Power BI Dashboard

# 📌 About This Project

This project is a Sales and Profit Analysis Dashboard created using Power BI and Excel.

The main purpose of this project is to understand sales performance, profit, products, categories, regions, and monthly business trends through an interactive dashboard.

# 🎯 Project Objectives

* Analyze total sales and total profit
* Track overall business performance
* Compare sales across different regions
* Identify the best-performing products
* Analyze profit by category
* Understand monthly sales trends
* Calculate profit margin
* Present business information in an easy-to-understand dashboard

# 🛠️ Tools Used

* Microsoft Power BI
* Microsoft Excel
* DAX
* Data Cleaning
* Data Visualization
* Business Intelligence

# 📂 Dataset

The dataset contains sample sales transactions with information such as:

* Order ID
* Order Date
* Customer ID
* Product
* Category
* Region
* Quantity
* Unit Price
* Discount
* Sales
* Cost
* Profit

## 📊 Dashboard

The dashboard includes:

# Key Performance Indicators

* Total Sales
* Total Profit
* Total Orders
* Total Quantity
* Profit Margin

# Visualizations

* Monthly Sales Trend
* Sales by Region
* Profit by Category
* Top Products
* Sales and Profit Analysis

# Filters

* Date
* Region
* Category
* Product

🧮 DAX Measures

The following measures were used in Power BI:

```DAX
Total Sales = SUM(Sales_Data[Sales])

Total Cost = SUM(Sales_Data[Cost])

Total Profit = SUM(Sales_Data[Profit])

Total Quantity = SUM(Sales_Data[Quantity])

Total Orders = DISTINCTCOUNT(Sales_Data[Order_ID])

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```
 #💡 Business Insights

After completing the dashboard, the following areas can be analyzed:

* Which region generates the highest sales?
* Which category generates the highest profit?
* Which products perform the best?
* Which month has the highest sales?
* What is the overall profit margin?
* Which products or regions need improvement?

 📸 Dashboard Preview

Dashboard screenshots will be added here after completing the Power BI dashboard.

 📁 Project Files

* `Sales_Profit_PowerBI_Dataset.xlsx` — Sales dataset
* `Sales_Profit_Dashboard.pbix` — Power BI dashboard
* `dashboard-overview.png` — Dashboard screenshot

 👩‍💻 Author

**Akshitha Reddy**

Aspiring Data Analyst

Skills: Power BI | Excel | SQL | Python | Data Analytics

 ⭐ Project Status

Completed as a portfolio project to demonstrate practical skills in data analysis, business intelligence, data visualization, and Power BI dashboard development.
