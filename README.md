# DSA3050A Advanced Power BI Exam

## Student Information
- **Student Name:** Zakariya Shafi  
- **Admission Number:** 596  
- **Course Code:** DSA 3050A  
- **Class:** SS 2026 End Semester Exam  


## Project Overview
This project presents an advanced Power BI analytical solution developed using the Superstore Sales dataset. The aim of the project was to transform raw retail transaction data into an interactive business intelligence dashboard that supports performance monitoring, time-based analysis, customer analysis, and product-level evaluation.


## Problem Statement
Retail businesses generate large amounts of transactional data, but raw data alone does not provide enough insight for decision-making. Without a proper analytical system, it becomes difficult to identify revenue trends, profitable categories, customer patterns, and areas of underperformance. This project addresses that problem by building a Power BI dashboard that enables data-driven decision-making.


## Dataset Description
The dataset used for this project is the **Superstore Sales Dataset**, obtained from a public source and imported into Power BI in CSV format. The dataset contains retail transaction data including order details, customer details, product information, sales, profit, quantity, and date fields.

### Key fields include:
- Order ID
- Order Date
- Customer ID
- Product ID
- Product Name
- Category
- Sub-Category
- Sales
- Profit
- Quantity
- Region
- Segment

The dataset was suitable for advanced Power BI analysis because it contains:
- numerical variables
- categorical variables
- time fields
- enough records for meaningful analysis
- fields that support star schema modeling
  

## Tools Used
- **Power BI Desktop**
- **Power Query**
- **DAX**
- **GitHub**


## Steps Followed

### 1. Data Acquisition and Understanding
- Selected the Superstore Sales dataset
- Reviewed columns and variables
- Identified business problem and analysis objectives

### 2. Data Cleaning and Transformation
Performed the following in Power Query:
- corrected data types
- removed unnecessary columns
- handled missing values
- removed duplicates
- cleaned text fields
- standardized categories
- created conditional columns
- extracted date parts
- split customer name column

### 3. Data Modeling
Created a star schema consisting of:
- **Fact Table:** Superstore Dataset
- **Dimension Tables:** DimCustomer, DimProduct, DimDate

Relationships were created using:
- Customer ID
- Product ID
- Order Date / Date

### 4. DAX Measures and Calculated Columns
Created calculated columns and advanced DAX measures for financial analysis, customer analysis, time intelligence, and ranking.

### 5. Dashboard Development
Developed 3 interactive report pages:
- Executive Summary
- Detailed Analysis
- Insights and Performance Monitoring

### 6. Analysis and Recommendations
Interpreted dashboard findings and developed analytical insights and business recommendations.


## Dashboard Features

### Page 1: Executive Summary
- KPI cards
- revenue trend chart
- revenue by category chart
- slicers for year, segment, category, and region

### Page 2: Detailed Analysis
- drill-down visual
- matrix table
- decomposition tree
- scatter chart for revenue vs profit

### Page 3: Insights and Performance Monitoring
- time intelligence comparison
- top-performing products
- performance comparison charts
- interactive slicers and cross-filtering


## Key DAX Measures
The following key DAX measures were created:
- Total Revenue
- Gross Profit
- Profit Margin %
- Year-to-Date Revenue
- Previous Period Revenue
- Growth %
- Top Category Rank
- Distinct Customers
- Average Order Value
- Total Orders

### Calculated Columns
- Profit Status
- Sales Band


## Key Insights
1. Revenue shows a declining trend after peak months, suggesting seasonality.
2. Technology is the strongest revenue-generating category.
3. Revenue is concentrated in a small number of top-performing products.
4. Some products generate revenue but contribute less profit, suggesting efficiency issues.
5. Year-to-date revenue is generally lower than the previous period, indicating weaker recent performance.
6. Regional differences suggest uneven market performance.


## Challenges Encountered
- creating a proper star schema after initially merging tables
- handling duplicate values when creating relationships
- ensuring the Date table worked correctly for time intelligence
- formatting dashboard visuals consistently
- building analytical visuals that remain clear and business-friendly


## Conclusion
This project demonstrates the use of Power BI as a complete business intelligence solution. Through data cleaning, relational modeling, DAX calculations, and dashboard design, raw retail data was transformed into meaningful business insights. The final dashboard enables performance monitoring, trend analysis, and strategic decision-making.


## Repository Structure

```text
DSA3050A-Advanced-PowerBI-Exam-Zakariya-Shafi-596/
│
├── data/
├── screenshots/
├── report/
├── powerbi/
├── README.md
└── dashboard_link/
