# Zepto-E-commerce-SQL-Data-Analyst-Project
This is a complete, real-world data analyst portfolio project based on an e-commerce inventory dataset scraped from Zepto — one of India’s fastest-growing quick-commerce startups. This project simulates real analyst workflows, from raw data exploration to business-focused data analysis.

**Project Overview**
The goal is to simulate how actual data analysts in the e-commerce or retail industries work behind the scenes to use SQL to:

--- Set up a messy, real-world e-commerce inventory database

--- Perform Exploratory Data Analysis (EDA) to explore product categories, availability, and pricing inconsistencies

--- Implement Data Cleaning to handle null values, remove invalid entries, and convert pricing from paise to rupees

--- Write business-driven SQL queries to derive insights around pricing, inventory, stock availability, revenue and more

**Dataset Overview**
The dataset was sourced from Kaggle.

- Columns:

name: Product name as it appears on the app

category: Product category like Fruits, Snacks, Beverages, etc.

mrp: Maximum Retail Price (originally in paise, converted to ₹)

discountPercent: Discount applied on MRP

discountedSellingPrice: Final price after discount (also converted to ₹)

availableQuantity: Units available in inventory

weightInGms: Product weight in grams

outOfStock: Boolean flag indicating stock availability

quantity: Number of units per package (mixed with grams for loose produce)

**Project Workflow**
Here’s a step-by-step breakdown of what we do in this project:

1. Database & Table Creation
2. Data Import - Loaded CSV.
3. Data Exploration
Counted the total number of records in the dataset

Viewed a sample of the dataset to understand structure and content

Checked for null values across all columns

Identified distinct product categories available in the dataset

Compared in-stock vs out-of-stock product counts

4. Data Cleaning
Identified and removed rows where MRP or discounted selling price was zero

Converted mrp and discountedSellingPrice from paise to rupees for consistency and readability

5. Business Insights
Found top 10 best-value products based on discount percentage

Identified high-MRP products that are currently out of stock

Estimated potential revenue for each product category

Filtered expensive products (MRP > ₹500) with minimal discount

Ranked top 5 categories offering highest average discounts

Calculated price per gram to identify value-for-money products

Grouped products based on weight into Low, Medium, and Bulk categories

Measured total inventory weight per product category


Let’s connect professionally and grow your data career
💡 Thanks for checking out the project! Your support means a lot — feel free to star ⭐ this repo or share it with someone learning SQL.🚀
