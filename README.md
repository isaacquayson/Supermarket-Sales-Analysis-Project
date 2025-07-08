# Supermarket-Sales-Analysis-Project

## Project Overview
This project focuses on end-to-end data analysis of a supermarket's sales records. It includes raw data cleaning, performance analysis through pivot tables, and the development of an interactive dashboard. The goal is to uncover key business insights and present them in a visually compelling format to support strategic decision-making.

---

## Objectives
- Clean and transform raw transactional data.
- Perform exploratory data analysis (EDA).
- Generate business insights using pivot tables.
- Build an interactive dashboard for reporting.
- Prepare the dataset for future predictive modeling.

---

## Tools Used
- **Microsoft Excel** – Data cleaning, pivot tables, dashboards
- * Python, Power BI
- **Data Types** – Categorical (Gender, Location), Numerical (Quantity, Unit Price)

---

## Data Description

### Raw Data (`DIRTY DATA`)
- 250 records with missing values, extra spaces, and inconsistent formats.

### Clean Data (`CLEAN DATA`)
- 221 cleaned records with the following fields:
  - `Invoice_ID`
  - `Customer_Name`
  - `Gender`
  - `Product_Category`
  - `Product_Name`
  - `Quantity`
  - `Unit_Price`
  - `Payment_Method`
  - `Date`
  - `Location`
  - `Total Amount`

### Pivot Tables & Dashboard
- Aggregated data used for deep analysis and visual presentation.

---

## Data Cleaning Steps
- Removed extra spaces and special characters.
- Fixed total amount formula errors (`Quantity × Unit Price`).
- Standardized column names and date formats.
- Removed duplicates and filled/reviewed missing values.

---

## Analysis Highlights
- Top-selling products and categories identified.
- Highest-revenue locations surfaced.
- Payment method patterns analyzed.
- Customer buying trends visualized by gender and location.

---

## Dashboard Features
- **KPI Cards**: Total Sales, Average Order Value, Total Items Sold
- **Line Chart**: Monthly sales trend
- **Bar Chart**: Product category performance
- **Filters**: By gender, product, location, payment method

---

## Key Business Questions Answered
- What are the best-performing products and categories?
- Which customer locations generate the most revenue?
- How are payment methods distributed across sales?
- What is the monthly trend of sales?

---

## Future Improvements
- Expand with Power BI or Python visualizations.
- Build predictive models for demand and segmentation.
- Automate dashboard updates with real-time data.

---

## Key Findings & Insights

1. **Top Product Category**: The most purchased items belonged to the `Beverages` and `Snacks` categories, accounting for a large portion of total revenue.
2. **Customer Demographics**: Female customers slightly outpaced males in overall sales volume, but men had a higher average purchase value.
3. **Location Trends**: The `Accra` branch generated the highest revenue, followed by `Kumasi`, while `Tamale` recorded fewer transactions.
4. **Peak Sales Periods**: The highest sales volume occurred in December, indicating strong seasonal trends that align with festive shopping behavior.
5. **Payment Preferences**: `Cash` was the most used payment method, suggesting potential gaps in card or digital payment adoption.
6. **Average Order Value (AOV)**: The average customer spent approximately **GHS 115–125** per transaction.

---

## Recommendations

1. **Boost Inventory for Top Products**: Ensure sufficient stock of high-performing items, especially in Beverages and Snacks.
2. **Target High-Value Customers**: Design marketing campaigns targeting male customers with premium product bundles, given their higher average order value.
3. **Digital Payment Promotion**: Encourage the use of non-cash payment methods via incentives or awareness campaigns.
4. **Holiday Sales Strategy**: Plan marketing and inventory strategies ahead of the festive season (October–December).
5. **Branch-Specific Strategy**: Investigate reasons behind lower sales in Tamale and explore localized promotions or partnerships.
6. **Customer Loyalty Program**: Implement reward systems to retain high-spending and repeat customers.

---

## Future Improvements
- Expand with Power BI or Python visualizations.
- Build predictive models for demand and segmentation.
- Automate dashboard updates with real-time data.
