Superstore Sales Analysis — Excel

Project Overview

This project analyzes the Superstore sales dataset using Microsoft Excel. The objective was to explore sales, profitability, customer segments, regional performance, product/category performance, order returns, and sales trends, and then present the findings through an interactive Excel dashboard.

This was my first complete Excel data analytics project, covering the workflow from data preparation and exploratory analysis to PivotTables, PivotCharts, slicers, dashboard creation, and business insights.

#Objectives

Analyze overall sales and profitability

Compare performance across categories, regions, and customer segments

Analyze sales and profit trends over time

Identify top-performing customers and products

Analyze returned orders and return rate

Calculate and compare profit margins

Build an interactive Excel dashboard

Translate the analysis into clear business insights

#Dataset

The project uses the Superstore sales dataset.

Key fields include:

Order ID

Order Date

Ship Date

Ship Mode

Customer ID

Customer Name

Segment

Country

City

State

Postal Code

Region

Product ID

Category

Sub-Category

Product Name

Sales

Quantity

Discount

Profit

A separate Returns sheet was also used to identify returned orders.

#Data Preparation

The data preparation stage included:

Checking the dataset structure and data types

Standardizing date formatting

Formatting Sales and Profit as currency

Creating Profit Margin

Creating a Discount Level classification

Handling profit values represented by dash/blank-like entries

Creating a return indicator by matching Order IDs with the Returns data

Checking for duplicates and data consistency

Preparing the data for PivotTables and dashboard analysis

Analysis Performed

#Basic Analysis

The initial analysis covered:

Total Sales

Total Profit

Total Quantity

Total Orders

Average Sales

Average Profit

Average Discount

Profit Margin

Sales by Category

Profit by Category

Sales by Region

Profit by Region

Sales by Segment

Monthly Sales

Yearly Sales

Returned vs. Non-returned Orders

#PivotTable Analysis

PivotTables were used for deeper analysis, including:

Sales and profit by category

Sales and profit by region

Sales and profit by segment

Year-over-year sales

Monthly sales trends

Return status analysis

Top products

Top customers

Category and regional comparisons

Profitability comparisons

Dashboard

The final dashboard includes KPI cards, slicers, and charts to provide an interactive overview of the business.

#Key Dashboard Components

Total Sales

Total Orders

Total Profit

Return Rate

Profit Margin

Sales by Category

Profit by Category

Sales by Region

Monthly Sales Trend

Returned vs. Non-returned Orders

Interactive filters for:

Segment

Region

Category

Year

#Key Insights

1. Overall Performance

The business generated approximately $2.30M in sales and $286.4K in profit, resulting in an overall profit margin of approximately 12.47%.

There were 5,009 unique orders, with an order return rate of approximately 5.91%.

2. Category Performance

Technology generated the highest sales at approximately $836K and the highest profit at approximately $145K, with a profit margin of about 17.40%.

Furniture generated approximately $742K in sales, but only about $18.45K in profit, resulting in a much lower profit margin of approximately 2.49%.

This shows that high sales volume did not necessarily translate into high profitability.

3. Regional Performance

The West region generated the highest sales at approximately $725K and the highest profit at approximately $108K.

The West also recorded the highest regional profit margin at approximately 14.94%, while the Central region had the lowest at approximately 7.92%.

4. Segment Performance

The Consumer segment generated the highest sales at approximately $1.16M and the highest total profit at approximately $134K.

However, the Home Office segment recorded the highest profit margin at approximately 14.03%.

This demonstrates that the segment with the highest sales is not necessarily the segment with the highest profitability rate.

5. Yearly Sales Trend

Sales increased substantially after 2015.

2014: approximately $484K

2015: approximately $471K

2016: approximately $609K

2017: approximately $733K

2017 recorded the highest annual sales.

6. Monthly Sales Pattern

Sales varied considerably by month.

November recorded the highest monthly sales at approximately $352K, followed by December at approximately $325K.

February recorded the lowest monthly sales at approximately $60K.

The analysis therefore shows stronger sales activity during several later months of the year.

7. Returns

There were 296 returned orders out of 5,009 total orders, producing an order return rate of approximately 5.91%.

After accounting for sales associated with returned orders, net sales were approximately $2.12M, while net profit was approximately $263K.

8. Top Customers

The top 10 customers generated approximately $153.8K in sales.

The highest-sales customer in the analysis generated approximately $25K in sales.

9. Furniture and Regional Profitability

Furniture profitability varied considerably across regions.

Furniture generated a loss of approximately $2.87K in the Central region, while producing positive profit in the East, South, and West.

This indicates that Furniture performance differs substantially by region and could be investigated further using product-level, discount, and pricing analysis.

#Tools Used

Microsoft Excel 2019

Excel formulas and functions

Data cleaning

PivotTables

PivotCharts

Slicers

Conditional Formatting

Excel Tables

Basic exploratory data analysis

#Project Workflow

Raw Dataset
    ↓
Data Preparation & Cleaning
    ↓
Calculated Columns
    ↓
Basic Analysis
    ↓
PivotTable Analysis
    ↓
PivotCharts & Slicers
    ↓
Interactive Dashboard
    ↓
Business Insights

#Project Files

- `sample_-_superstore_raw data.xls` — Original dataset
- `superstore_analysis.xls` — Excel workbook containing the analysis, Pivot Tables, and dashboard
- `superstore_dashboard.png` — Preview of the final dashboard



#Conclusion

This project helped me apply Excel to a complete data analytics workflow rather than focusing only on individual Excel functions.

The analysis shows strong overall sales and profitability, but also highlights differences in profitability across categories, regions, and customer segments. In particular, the low profitability of Furniture compared with its sales contribution and the regional variation in Furniture performance are areas that would benefit from deeper analysis.

The project also provided practical experience with turning raw business data into analysis, visualizations, and actionable findings.

