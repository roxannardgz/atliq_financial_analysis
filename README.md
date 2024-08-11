# AtliQ - Financial Analysis

**Data Analyst Bootcamp** @ Tripleten<br>
Sprint 12 Project - Capstone

## Context and Overview
AtliQ Hardware is a leading computer hardware producer in India with presence in various countries across Europe, Latin America, and Asia. As a multinational entity, AtliQ supplies hardware to major players, including Amazon, Best Buy, and Walmart.

This year, AtliQ has requested a comprehensive audit of its sales operations and assistance in automating existing data processes. This project encompasses financial, product, and customer analyses. Specifically, the Data Analytics Department, in collaboration with AtliQ's Financial Department, is conducting a financial analysis for the period 2018–2022.

The dataset provided is in SQLite format, and the project includes data exploration, calculation of key metrics, and hypothesis testing. We have drawn conclusions and offered recommendations based on the insights gained during the analysis. Additionally, an interactive dashboard was created to present relevant metrics and insights, providing AtliQ with a valuable tool for ongoing and future use.

## Data

The database used contains the following tables:
* `dim_customers`: contains customer-related data.
* `dim_product`: contains product-related data.
* `fact_pre_discount`: contains pre-invoice deductions information for each customer.
* `fact_manufacturing_cost`: contains the cost incurred in the production of each product.
* `fact_gross_price`: contains gross price information for each product.
* `fact_sales_monthly`: contains monthly sales data for each product.

## Libraries Used

- **sqlite3**: Database connection and queries
- **pandas**: Data manipulation and analysis
- **seaborn**: Data visualization
- **matplotlib**: Plotting library (`matplotlib.pyplot`)
- **scipy**: Statistical analysis (`scipy.stats`)
