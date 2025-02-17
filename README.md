# Superstore Sales Analysis

This project analyzes sales data from a superstore to uncover trends in sales, profits, and product performance. The dataset includes information about orders, products, customers, and regions, making it ideal for exploring key business metrics.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Results](#results)
   - [Total Sales and Profit](#total-sales-and-profit)
   - [Sales by Category](#sales-by-category)
   - [Monthly Sales Over Time](#monthly-sales-over-time)
   - [Profit by Sub-Category](#profit-by-sub-category)
   - [Correlation Between Sales and Profit](#correlation-between-sales-and-profit)
5. [How to Run](#how-to-run)
6. [Conclusion](#conclusion)

---

## Introduction
Understanding sales data is critical for businesses to make informed decisions. This project analyzes a superstore's sales dataset to answer key questions, such as:
- What are the total sales and profits?
- Which product categories generate the most revenue?
- How do sales and profits vary over time and across regions?
- Is there a correlation between sales and profits?

The analysis is performed using Python, with visualizations created using Matplotlib and Seaborn.

---

## Dataset
The dataset used in this project is the **Superstore Dataset**, available on [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final). It contains the following columns:
- `Order Date`: The date of the order.
- `Category`: The category of the product (e.g., Furniture, Office Supplies, Technology).
- `Sub-Category`: The sub-category of the product (e.g., Chairs, Phones, Paper).
- `Sales`: The total sales for the order.
- `Profit`: The profit generated from the order.
- `Region`: The region where the order was placed.

---

## Methodology
The analysis involves the following steps:
1. **Data Loading**: The dataset is loaded into a Pandas DataFrame.
2. **Data Cleaning**: The `Order Date` column is converted to a datetime format for time-based analysis.
3. **Exploratory Data Analysis (EDA)**:
   - Calculate total sales and profits.
   - Analyze sales by product category and sub-category.
   - Examine monthly sales trends.
   - Explore the correlation between sales and profits.
4. **Visualization**: Key insights are visualized using Matplotlib and Seaborn.

---

## Results

### Total Sales and Profit
The superstore generated **total sales of $2,297,201** and **total profits of $286,397** during the period covered by the dataset.

### Sales by Category
The **Technology** category generated the highest sales, followed by **Furniture** and **Office Supplies**.

![Sales by Category](plots/sales_by_category.png)

### Monthly Sales Over Time
Sales show a general upward trend over time, with noticeable peaks during certain months (e.g., November and December, likely due to holiday shopping).

![Monthly Sales](plots/monthly_sales.png)

### Profit by Sub-Category
The **Copiers** sub-category generated the highest profits, while **Tables** resulted in a net loss.

![Profit by Sub-Category](plots/profit_by_subcategory.png)

### Correlation Between Sales and Profit
There is a positive correlation between sales and profits, with some outliers. For example, high sales do not always guarantee high profits, especially in the **Furniture** category.

![Sales vs Profit](plots/sales_profit_correlation.png)

---
