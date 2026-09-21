# Retail_store_Codeathon_project

🛍️ Retail Store Sales Analysis Dashboard

A Power BI Data Analytics project developed as part of a Codeathon to analyze retail store sales performance, product performance, customer behavior, and business trends.

The project transforms raw retail data into an interactive and professional dashboard that helps identify important patterns and generate actionable business insights.

📌 Project Overview

The Retail Store Sales Analysis Dashboard provides a detailed analysis of retail sales data using Microsoft Power BI.

The project focuses on:

📊 Overall sales and profit performance
📦 Product performance
👥 Customer analysis
🌍 Regional sales performance
💳 Payment method analysis
📈 Monthly sales and profit trends
💡 Business insights and recommendations
🎯 Objectives

The main objectives of this project are:

Clean and prepare the retail sales dataset.
Transform raw data into an analysis-ready format.
Create an interactive Power BI dashboard.
Analyze sales, profit, products, and customers.
Identify important business trends and patterns.
Generate useful insights and recommendations.
Demonstrate practical data analytics and visualization skills.
📊 Dashboard Structure

The Power BI report contains 4 main pages.

1️⃣ Overview

The Overview page provides a high-level summary of the business.

Key Performance Indicators
💰 Total Sales
💵 Total Cost
📈 Total Profit
📊 Profit Margin
🛒 Total Orders
📦 Total Quantity Sold
Visualizations
Monthly Sales & Profit Trend
Sales by Category
Sales by Region
Profit by Region
Sales by Payment Method
Interactive slicers for filtering the dashboard
2️⃣ Product Analysis

The Product Analysis page focuses on product and category performance.

Key Analysis
Top 10 Products by Sales
Top 10 Products by Profit
Sales by Category
Profit by Category
Quantity Sold by Category
Category Sales vs Profit

This page helps identify high-performing products and categories.

3️⃣ Customer Analysis

The Customer Analysis page provides insights into customer purchasing behavior.

Key Metrics
👥 Total Customers
💰 Total Customer Sales
🛒 Total Orders
📊 Average Order Value
🔄 Repeat Customers
🆕 New Customers
⭐ High-Value Customers

The page helps understand customer contribution to overall business performance.

4️⃣ Insights & Recommendations

The final page summarizes the major findings from the analysis.

Insights
Identify the highest-performing product categories.
Identify products generating the most sales and profit.
Analyze regional sales performance.
Understand customer purchasing patterns.
Compare sales and profitability across categories.
Identify areas with opportunities for improvement.
Recommendations
Focus marketing efforts on high-performing categories.
Improve sales strategies for underperforming products.
Analyze regional performance to identify growth opportunities.
Develop strategies to increase repeat purchases.
Focus on high-value customer segments.
Monitor profit margins along with sales growth.
🧹 Data Cleaning & Transformation

The dataset was prepared using Excel and Power Query.

The cleaning process included:

Handling missing values
Removing unnecessary records
Correcting data types
Cleaning text fields
Formatting date columns
Checking duplicate records
Transforming columns
Creating calculated fields
Preparing the dataset for Power BI analysis
📐 DAX Measures

Several DAX measures were created for the dashboard, including:

Total Sales = SUM(Sales[Sales])
Total Cost = SUM(Sales[Cost])
Total Profit = SUM(Sales[Profit])
Total Orders = DISTINCTCOUNT(Sales[Order_ID])
Total Quantity = SUM(Sales[Quantity])
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
Average Order Value = DIVIDE([Total Sales], [Total Orders], 0)

Note: The exact table and column names may differ depending on the final Power BI model.

📈 Key Features

✅ Interactive Power BI dashboard
✅ KPI cards
✅ Data filtering using slicers
✅ Product performance analysis
✅ Customer analysis
✅ Regional analysis
✅ Category analysis
✅ Profitability analysis
✅ Monthly trend analysis
✅ DAX calculations
✅ Data cleaning and transformation
✅ Insights and recommendations
💡 Business Value

This project demonstrates how raw retail data can be transformed into meaningful business information.

The dashboard can help businesses:

Monitor sales performance
Track profitability
Identify high-performing products
Understand customer behavior
Compare regional performance
Identify growth opportunities
Make data-driven business decisions
🚀 Future Improvements

Possible future enhancements include:

📈 Sales forecasting
👥 Advanced customer segmentation
📊 RFM analysis
🔄 Customer retention analysis
📅 Year-over-year analysis
🤖 Predictive analytics
🔗 Integration with live data sources
📱 Power BI mobile dashboard optimization
👨‍💻 Author

Muhammed Nabeel

🎓 B.Com Taxation
📊 Data Analytics Enthusiast
💼 Interested in Data Analytics, Business Intelligence & Power BI

⭐ Project

If you find this project useful, feel free to ⭐ star the repository and explore the dashboard.

Thank you for visiting! 🚀
