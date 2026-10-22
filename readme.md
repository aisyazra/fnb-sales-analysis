# F&B Sales Analysis

## Business Background

The dataset represents sales transactions from an anonymized Indonesian F&B business with multiple outlets in Surabaya, East Java.

The business records daily transaction data, including sales amount, products purchased, payment methods, outlet information, and loyalty card usage. The dataset covers transactions from January to September 2025 across three outlets.

This project uses the available transaction data to examine sales patterns and identify areas that may provide useful insights for business decision-making.

## Business Problem

The business needs to better understand its sales performance and customer transaction patterns across different outlets, products, payment methods, and time periods.

Without a clear view of these patterns, it can be difficult to identify which areas contribute most to sales and when transaction activity is highest.

This analysis aims to provide a data-driven view of the business's sales performance and uncover patterns that can support further business decision-making.

## Project Objectives

- Analyze key sales KPIs, including **Revenue, Order Volume, AOV (Average Order Value), and Items Sold**.
- Analyze sales trends and performance across different time periods.
- Compare **Revenue, Order Volume, and AOV** across different outlets.
- Identify top-performing products and categories based on sales volume.
- Understand payment method patterns and peak transaction hours.
- Examine loyalty card transaction patterns.
- Generate data-driven insights that can support business decision-making.

## Business Questions

1. What are the overall **Revenue, Order Volume, AOV, and Items Sold** during the analysis period?
2. How do **Revenue, Order Volume, and AOV** change over time?
3. How do **Revenue, Order Volume, and AOV** differ across outlets, and what contributes to the differences in outlet performance?
4. Which **products and categories** contribute the most to overall sales volume and product value?
5. Which **payment methods** are most frequently used, and how does **AOV** differ across payment methods?
6. What are the **peak transaction hours**, and how does transaction activity vary throughout the day?
7. What patterns can be observed in **loyalty card transactions**, particularly in terms of transaction volume and recorded sales value?

## Data Source

This project uses the **[Anonymous Transactional Dataset](https://data.mendeley.com/datasets/kcgf45y24m/2)**, publicly available on Mendeley Data.

The dataset originates from an anonymized food and beverage (F&B) micro, small, and medium-sized enterprise (MSME) operating multiple outlets in Surabaya, East Java, Indonesia. The original records were collected through the business's Point-of-Sale (POS) system between January and September 2025.

The dataset consists of two CSV files:

| Dataset | Description | Records |
|---|---|---:|
| Transactions | Transaction dates, times, outlets, sales amounts, purchased items, and payment information | 53,820 |
| Products | Product names, variants, categories, prices, and descriptions | 96 |

**Source:** [Mendeley Data — Anonymous Transactional Dataset, Version 2](https://data.mendeley.com/datasets/kcgf45y24m/2)

This project focuses on sales performance analysis using MySQL, with additional data preparation and transformation to support product-level and category-level analysis.

## Tools & Technologies

- **MySQL** — Data cleaning, transformation, and analysis
- **MySQL Workbench** — SQL development and database management
- **Git & GitHub** — Version control and project documentation# F&B Sales Analysis

## Business Background

The dataset represents sales transactions from an anonymized Indonesian F&B business with multiple outlets in Surabaya, East Java.

The business records daily transaction data, including sales amount, products purchased, payment methods, outlet information, and loyalty card usage. The dataset covers transactions from January to September 2025 across three outlets.

This project uses the available transaction data to examine sales patterns and identify areas that may provide useful insights for business decision-making.

## Business Problem

The business needs to better understand its sales performance and customer transaction patterns across different outlets, products, payment methods, and time periods.

Without a clear view of these patterns, it can be difficult to identify which areas contribute most to sales and when transaction activity is highest.

This analysis aims to provide a data-driven view of the business's sales performance and uncover patterns that can support further business decision-making.

## Project Objectives

- Analyze key sales KPIs, including **Revenue, Order Volume, AOV (Average Order Value), and Items Sold**.
- Analyze sales trends and performance across different time periods.
- Compare **Revenue, Order Volume, and AOV** across different outlets.
- Identify top-performing products and categories based on sales volume.
- Understand payment method patterns and peak transaction hours.
- Examine loyalty card transaction patterns.
- Generate data-driven insights that can support business decision-making.

## Business Questions

1. What are the overall **Revenue, Order Volume, AOV, and Items Sold** during the analysis period?
2. How do **Revenue, Order Volume, and AOV** change over time?
3. How do **Revenue, Order Volume, and AOV** differ across outlets, and what contributes to the differences in outlet performance?
4. Which **products and categories** contribute the most to overall sales volume and product value?
5. Which **payment methods** are most frequently used, and how does **AOV** differ across payment methods?
6. What are the **peak transaction hours**, and how does transaction activity vary throughout the day?
7. What patterns can be observed in **loyalty card transactions**, particularly in terms of transaction volume and recorded sales value?

## Dataset

The dataset contains transaction and product information from an anonymized Indonesian F&B business in Surabaya, East Java.

### Transactions
- **53,820 transactions**
- **3 outlets**
- **January–September 2025**
- 11 transaction-level attributes, including sales amount, date, time, outlet, payment method, items purchased, and loyalty card usage.

### Products
- **96 products**
- Product-level information including product name, variant, category, price, and description.

The transaction and product datasets were combined during the data preparation stage to enable product- and category-level analysis.

## Tools & Technologies

- **MySQL** — Data cleaning, transformation, and analysis
- **MySQL Workbench** — SQL development and database management
- **Git & GitHub** — Version control and project documentation
