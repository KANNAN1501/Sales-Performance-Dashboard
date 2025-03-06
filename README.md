# Power BI Sales Performance Dashboard 📊

## Introduction

This repository contains a Power BI dashboard designed to analyze and visualize sales performance across different dimensions such as time, product, and geography. The dashboard leverages three key datasets to provide insights into sales trends, profitability, and key performance indicators (KPIs).

## Dataset Overview

### 1. PLANT FACT (Sales Data)

This table contains transactional sales data with the following fields:

Sales_USD: Revenue in USD

Quantity: Units sold

Price_USD: Selling price per unit

COGS_USD: Cost of goods sold in USD

Date_Time: Date of transaction

Account_id: Unique account identifier

2. ACCOUNT (Customer Data)

This table contains details about customer accounts:

country_code: Country code of the account

Account: Account name

Master_id: Master account ID

Account_id: Unique account identifier (links to PLANT FACT table)

latitude2, longitude: Geolocation of the account

country2: Country name

Postal_code: Postal code of the account

street_name, Street_number: Address details

3. PLANT HIERARCHY (Product Data)

This table provides a classification of products:

Product_Family: Broad product category

Product_Family_Id: Product family identifier

Product_Group: Sub-category within the product family

Product_Group_id: Product group identifier

Product_Name: Specific product name

Product_Name_id: Unique product name identifier

Product_Size: Product size classification

Product_Type: Type of product

Dashboard Visualizations

Waterfall Chart

Analysis: Year-to-date (YTD) vs. Previous Year-to-date (PYTD)

Breakdown: By product, month, and country

Line and Column Stacked Chart

Focus: YTD and PYTD trends

Breakdown: By month and product type

TreeMap

Purpose: Identify the bottom 10 performing countries based on YTD vs. PYTD sales

Scatter Chart

Analysis: Account profitability segmentation

Metrics: Gross Profit Percentage (GP%) vs. Quantity

KPI Cards

Purpose: Display key performance indicators (KPIs) for quick business insights

Getting Started

Clone this repository to your local machine:

git clone https://github.com/yourusername/your-repo-name.git

Open the Power BI file (.pbix) in Power BI Desktop.

Ensure data sources are properly connected.

Explore the dashboard and interact with the visualizations.

Contributions

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

License

This project is licensed under the MIT License.
