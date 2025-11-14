# zepto_sql_data_analysis_project
End-to-end SQL project demonstrating data cleaning, EDA, and analytical queries on e-commerce (Zepto) product data.

🌟 Zepto SQL Data Analysis

📦 End-to-end SQL Data Cleaning, Exploration & Business Insights Project

🧾 Overview

This project showcases a complete SQL workflow built on real-world e-commerce data inspired by Zepto.
It demonstrates strong skills in:

✔️ Data Cleaning

✔️ Data Exploration

✔️ Analytical SQL

✔️ Business Insight Generation

The project is perfect for portfolios, showcasing your ability to turn raw data into actionable insights using SQL only.

🛠️ Tech Stack

🧱 Database Schema
Table Name: zepto

Column Name	Description
sku_id	Unique product identifier (Primary Key),
category	Product category,
name	Product name,
mrp	Maximum retail price,
discountPercent	Discount percentage offered,
availableQuantity	Stock quantity available,
discountedSellingPrice	Final selling price after discount,
weightInGms	Product weight in grams,
outOfStock	Stock status (TRUE/FALSE),
quantity	Quantity sold or packaged

🔍 Data Exploration Highlights

✨ The script includes:

Row count,
Sample data view,
Null-checking across all fields,
Stock distribution (in-stock vs out-of-stock),
Products appearing multiple times,
List of unique categories,
This establishes a strong foundation before analysis.

🧼 Data Cleaning Performed

🧹 Key Cleaning Steps

Removed records where MRP = 0
Converted paise → rupees
Standardized pricing fields
Ensured no nulls in critical fields

These steps ensure cleaner analysis and improved reliability.

📊 Analytical Insights
1️⃣ Top 10 Best-Value Products

Sorted by highest discount percentage.

2️⃣ High-MRP Items That Are Out of Stock
Reveals demand-heavy products worth restocking.

3️⃣ Estimated Revenue by Category
SUM(discountedSellingPrice × availableQuantity)

4️⃣ Premium Products with Low Discounts
Products with MRP > ₹500 and discount < 10%.

5️⃣ Categories with Highest Avg Discount %
Shows which categories have strongest promotional activity.

6️⃣ Price per Gram Analysis
Highlights best-value products for >100g items.

7️⃣ Weight Category Classification
Products grouped into:

🟩 Low (< 1kg)

🟨 Medium (1–5kg)

🟥 Bulk (> 5kg)

8️⃣ Total Inventory Weight by Category

Calculates inventory load across categories.
📂 SQL File
Zepto_SQL_data_analysis.sql — complete script including:
Table creation
Data cleaning
Exploratory queries
Business queries


🌈 What This Project Demonstrates

🔹 SQL proficiency in end-to-end data cleaning
🔹 Ability to extract real business insights
🔹 Experience working with messy, real-life style datasets
🔹 Strong portfolio-ready analytics workflow
