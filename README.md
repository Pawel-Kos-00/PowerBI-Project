# Maven Market Sales Report - Power BI Project

## Overview

This project utilizes a dataset from Maven Analytics to create a comprehensive **sales report** using **Power BI**. The report covers data from the period **1997-1998**, focusing on key business metrics such as **sales** and **returns**. The main objective is to visualize the data in an interactive and insightful manner, providing valuable business intelligence.

## Dataset Description

The data consists of:
- **Fact Tables**:
  - **Sales**: Transactional sales data from the reporting period.
  - **Returns**: Information on product returns.

- **Dimension Tables**:
  - **Customers**: Contains different inormations about customers.
  - **Products**: Details on products, including categories and prices.
  - **Regions**: Geographical data for regional sales analysis.
  - **Calendar**: Time-based data enabling analysis by year, quarter, month, etc.
  - **Stores**: Information on store locations, including region and size for store-level analysis.

## Data Model

The report uses a **snowflake schema**, where dimension tables (such as Customers, Products, Regions, Calendar, and Stores) are connected to the fact tables (Sales and Returns). This structure enables flexible, drill-down analysis of the data.

## Power BI Features

The report is organized into four primary dashboards:
1. **Home Dashboard**: Provides an overview of key performance indicators (KPIs) like total sales, returns, and profit margins.
2. **Map Dashboard**: Displays a geographical breakdown profitability, highlighting performance by region.
3. **Product Dashboard**: Delivers product-level insights, including best-selling items and return rates.
4. **Customer Dashboard**: Focuses on customer behavior, demographics, and purchasing patterns.

## Tools and Technologies

- **Power BI**: The primary tool used for data visualization and reporting.
- **DAX**: Advanced calculations using Data Analysis Expressions for deriving key business metrics.

## Conclusion

This project demonstrates the power of **Power BI** to transform raw sales, returns, and store data into actionable insights through well-structured visualizations. The interactive dashboards provide a complete view of business performance, helping uncover critical trends for decision-making.

