# Sales Performance & Profitability Dashboard

## Dashboard Preview

![Sales Performance & Profitability Dashboard](Screenshots/Final_Dashboard.png)

---

## Project Overview

This project is an interactive Sales Performance & Profitability Dashboard developed using Microsoft Excel.

The project analyzes sales transaction data to understand sales performance, profitability, customer behavior, product performance, regional performance, and payment-method trends.

The workflow covers the complete data analysis process:

**Raw Data → Data Preparation → Data Modeling → DAX Analysis → Dashboard → Business Insights**

---

## Business Problem

Businesses need to monitor sales and profitability across different products, regions, customers, and payment methods.

The objective of this project is to transform raw sales transaction data into an interactive dashboard that helps business users quickly understand performance and identify important business trends.

---

## Objectives

- Analyze overall sales performance
- Measure total profit and profitability
- Track total orders and customers
- Calculate Average Order Value
- Analyze sales performance by region
- Identify top-performing products
- Analyze payment-method performance
- Create interactive KPIs and visualizations
- Generate actionable business insights

---

## Tools & Technologies

- Microsoft Excel
- Power Query
- Power Pivot
- DAX
- PivotTables
- PivotCharts
- Slicers
- Timeline Filters
- Data Modeling
- Data Visualization

---

## Dataset

The project uses sales transaction data containing information related to:

- Order details
- Customer information
- Product information
- Region
- Sales amount
- Profit
- Payment method
- Order date

The dataset is included in this repository:

`Dataset/Sales_Data.xlsx`

---

## Data Preparation

Power Query was used to prepare the raw dataset for analysis.

Key data preparation activities included:

- Removing unnecessary data
- Checking data quality
- Handling missing or inconsistent values
- Correcting data types
- Formatting date fields
- Preparing the dataset for analysis
- Loading the cleaned data into the Excel data model

---

## Data Model

Power Pivot was used to create the data model and establish relationships between the required tables.

The data model supports analysis across:

- Products
- Customers
- Sales
- Regions
- Dates
- Payment Methods

This model allows dashboard calculations and visualizations to work consistently across different filters.

---

## DAX Measures

DAX was used to create key performance indicators and analytical measures.

### Total Sales

```DAX
Total Sales := SUM(Sales[Sales_Amount])
```
### Total Profit
```DAX
Total Profit := SUM(Sales[Profit])
```
### Total Orders
```DAX
Total Orders := DISTINCTCOUNT(Sales[Order_ID])
```
### Total Customers
```DAX
Total Customers := DISTINCTCOUNT(Sales[Customer_ID])
```
### Average Order Value
```DAX
Average Order Value := DIVIDE([Total Sales], [Total Orders])
```
### Profit Margin %
```DAX
Profit Margin % := DIVIDE([Total Profit], [Total Sales])
```
## Top Product

A DAX calculation was used to identify the product with the highest sales performance.

## Top Region

A DAX calculation was used to identify the region with the highest sales performance.

## Dashboard

The dashboard provides an interactive view of sales and profitability performance.

## KPI Cards

The dashboard includes:

Total Sales
Total Profit
Total Orders
Total Customers
Average Order Value
Profit Margin %
Top Product
Top Region

## Charts & Analysis

The dashboard provides visual analysis of:

Sales performance by region
Product performance
Category performance
Payment-method performance
Sales and profitability trends
Top-performing products

## Filters

Interactive filters such as:

Slicers
Timeline filters
Product filters
Region filters

allow users to explore the data dynamically.

## Business Insights

The dashboard analysis produced the following key business insights:

South region recorded the highest sales performance.
Computers were among the highest-performing product categories.
Mobile products showed strong sales performance.
UPI recorded the highest sales among the analyzed payment methods.
Laptop 15 was one of the top-performing products.

These insights help identify regional performance, product demand, and customer payment preferences.

## Key Skills Demonstrated
Microsoft Excel
Data Cleaning & Preparation
Power Query
Data Modeling with Power Pivot
DAX Measures
Pivot Tables & Pivot Charts
Interactive Dashboard Development
KPI Development
Data Visualization
Business Insights & Reporting
Slicers & Timeline Filters
Data Analysis

## Screenshots

Data Model

DAX Measures

Final Dashboard

## Project Files

Sales-Performance-Profitability-Dashboard
│
├── README.md
│
├── Sales_Performance_Profitability_Dashboard.xlsx
│
├── Dataset
│   └── Sales_Data.xlsx
│
├── Documentation
│   └── Sales_Performance_Project_Documentation.docx
│
└── Screenshots
    ├── Data_Model.png
    ├── DAX_Measures.png
    └── Final_Dashboard.png
    
## Conclusion

This project demonstrates the complete process of transforming raw sales data into an interactive business dashboard using Microsoft Excel.

Power Query was used for data preparation, Power Pivot for data modeling, and DAX for analytical calculations.

The dashboard provides insights into sales performance, profitability, customers, products, regions, and payment methods.

The project demonstrates practical skills in Excel-based data analysis, dashboard development, KPI creation, data visualization, and business reporting.

## Project Status

Completed

Project Type: Data Analyst Portfolio Project

Tools: Excel | Power Query | Power Pivot | DAX


---

# Step 4 — Preview BEFORE committing

After pasting everything:

1. **Do NOT click Commit immediately.**
2. Click **Preview changes**.
3. Scroll through the entire README.

You should see:

**Dashboard Preview**  
→ Your dashboard image

**Project Overview**

**Business Problem**

**Objectives**

**Tools & Technologies**

**Dataset**

**Data Preparation**

**Data Model**

**DAX Measures**

**Dashboard**

**Business Insights**

**Key Skills Demonstrated**

**Screenshots**

**Conclusion**

---

# ⚠️ Important: Check the images

Your GitHub folder must be named **exactly**:

```text
Screenshots

And inside it:

Final_Dashboard.png
Data_Model.png
DAX_Measures.png
 ```
The README uses:

Screenshots/Final_Dashboard.png
Screenshots/Data_Model.png
Screenshots/DAX_Measures.png

