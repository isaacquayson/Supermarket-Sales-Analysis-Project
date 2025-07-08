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
