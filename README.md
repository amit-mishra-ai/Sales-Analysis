# 📊 Sales Analysis Project

## Overview
This mini project analyzes historical sales data to uncover business insights such as revenue trends, top-performing cities, optimal advertising times, and product purchasing patterns.  
The goal is to demonstrate **data cleaning, exploratory data analysis (EDA), and insight generation** using Python.

This project is ideal for showcasing practical data analysis skills commonly used in real-world business scenarios.

---

## Objectives
- Clean and preprocess raw sales data
- Combine monthly datasets into a single, analysis-ready dataframe
- Answer key business questions using data-driven insights
- Visualize trends to support decision-making

---

## Dataset
- Monthly sales CSV files (merged during analysis)
- Includes order dates, product names, prices, quantities, and purchase locations

---

## Tools & Technologies
- **Python**
- **Pandas** – data cleaning and manipulation
- **Matplotlib** – data visualization
- **Jupyter Notebook** – analysis workflow and documentation

---

## Key Steps Performed

### 1. Data Cleaning
- Removed rows with missing values (NaN)
- Filtered out invalid or malformed order dates
- Converted columns to appropriate data types (dates, integers, floats)

### 2. Feature Engineering
- Added **Month** column for time-based analysis
- Extracted **City** information from purchase addresses
- Created a **Sales** column (price × quantity)

### 3. Exploratory Data Analysis
Answered several business-critical questions:

- 📈 **Best month for sales** and total revenue generated
- 🏙️ **Top-performing city** by total sales
- ⏰ **Optimal time for advertisements** based on purchase frequency
- 🛒 **Products frequently bought together**
- ⭐ **Most sold product** and reasoning behind its performance

---

## Sample Insights
- Sales peak during specific months, indicating seasonality
- Certain cities consistently outperform others in revenue
- Ads are most effective when shown during high purchase-frequency hours
- Some products have strong cross-selling opportunities

