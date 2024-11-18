# Retail Sales Analysis Using SQL and Python

### Project Overview

This project analyzes retail sales data from an online store using SQL and Python. The dataset contains information about transactions, including product descriptions, quantities sold, prices, and customer details. The goal of this project is to uncover insights about sales trends, customer behavior, and product performance.

#### Key Objectives

- Analyze sales trends over time.
- Identify the most popular products and their sales quantities.
- Explore customer spending behavior and segment top customers.
- Investigate sales performance across countries.
- Visualize key metrics to gain actionable insights.

### Dataset Information

The dataset is provided in the file Online retail.zip, which contains the Excel file online_retail_II.xlsx. It includes the following fields:

- Invoice: Unique identifier for each transaction.
- StockCode: Unique product code.
- Description: Description of the product.
- Quantity: Number of items purchased.
- InvoiceDate: Date of the transaction.
- Price: Unit price of the product.
- Customer ID: Unique identifier for each customer.
- Country: Country where the transaction occurred.

#### Data Summary

- Number of Records: 407,695
- Number of Fields: 8
- File Format: Excel (.xlsx)

### Steps in the Project

#### Data Loading and Cleaning:
- Extracted the dataset from a .zip file.
- Loaded the data into a Pandas DataFrame.
- Renamed columns to make them SQL-friendly.
- Saved the data to an SQLite database for querying.

#### Data Analysis Using SQL:
- Analyzed total sales per country.
- Identified top-selling products and their quantities.
- Tracked monthly sales trends.
- Found the top customers based on their spending.
- Determined the best-performing sales days.

### Visualizations:

- Monthly sales trends over time.
- Total sales by country.
- Top-selling products.

### Key Findings

- The top countries contributing to sales are primarily the UK, the USA, and Germany.
- Certain products dominate sales due to high demand.
- Monthly sales trends indicate potential seasonality in purchasing behavior.
- A small percentage of customers account for a significant proportion of sales.

### Future Work

- Perform advanced customer segmentation using RFM (Recency, Frequency, Monetary) analysis.
- Explore machine learning models to predict future sales trends.
- Create an interactive dashboard for real-time retail analytics.

### Source

https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset
