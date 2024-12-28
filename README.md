# SuperStore Sales Analysis
## Overview
The SuperStore Sales Analysis Dashboard provides a comprehensive analysis of sales and its related metrics across three keys dimensions: Sales, Product, and Customer (overview). This dashboard is designed to offer detailed insights into sales generation, year-on-year change, product and customer statistics while allowing users to filter data by parameters such as date, product, category, subcategory, city, state, region, and customer segment. In this project, you will analyze the sales data, highlighting the profits in every dimension, overall sales, and other vital factors impacting the business outcomes. This report is a part of descriptive analysis.

## Aim
The primary goal is to provide actionable insights for the SuperStore by analyzing its historical data, pinpointing areas for enhancement and growth through comprehensive analysis.

## Installation
To run this project, ensure you have Microsoft Power BI installed on your system.

## Tools Utilized
1. Microsoft Power BI
2. Power Query
3. DAX Query

## Skills Practiced
1. Data Cleaning and importing
2. Data Normalization
3. Data Modeling (Star Schema)
4. Data Manipulation
5. Data Visualization

## Data Modeling (Star Schema)
![Data_Modeling](https://github.com/user-attachments/assets/607305e7-66a6-4326-880e-32341552ea04)

## Dashboard
![1](https://github.com/user-attachments/assets/f5680e4d-8824-4cf5-807c-1866b56e4664)
![2](https://github.com/user-attachments/assets/e5dd4b58-c853-4c1f-813c-d4388e017eaa)
![3](https://github.com/user-attachments/assets/34eff9a1-5cbd-45ff-8c77-dd0f807b72a4)
![4](https://github.com/user-attachments/assets/ff761dbb-f725-41bd-b2a2-dc8244e044eb)

## Dashboard Insights
1. Key Performance Indicators (KPIs):
  1. Sales Overview
     - Total sales
     - Total Orders
     - Average Order Value (AOV)
     - Year-on-Year Change(%)
    
  2. Product Overview
     - Total products
     - Total categories
     - Total sub-categories
     - Most sold product

  3. Customer Overview
     - Total customers
     - Total cities

2. Yearly Trends: 
   - Total sales by year (overall)
   - Total orders by category (yearly, monthly)
   - Top 3 most sold products (sale trend)

3. Categorical Analysis:
   - Total sales by category, sub-category
   - Total orders by year
   - Top 5 customers by sales
   - Top 5 Selling Products
   - Total products by category, sub-category
   - Total customers by segment, region, state, city
   - Customers with most unique products purchased
     
4. Filters: Month, Year, Product name, Category, Sub-category, City, State, Region, Segment

5. Slicers: Year

## Project Learnings
- Importing the raw master data using the Power BI's data importing method (Import Storage Mode).
- Cleaning the data by importing and transform in Power Query.
- Normalizing the master data by creating multiple tables with relevant fields of different dimensions, which is to help reducing data redundancy and improve querying performance.
- Modeling the data using the star schema technique by creating fact and dimension tables.
- Manipulating the data by aggregating to find key metrics with the DAX expressions.
- Creation of interactive dashboards for SuperStore sales data analysis
- Utilization of complex parameters for drill-down analysis and filter customization
- Data manipulation techniques: connections, table joins, calculations, and user-driven parameters for visualization
- Various visualization types used: bar chart, pie chart, clustered bar chart, line chart, filters, slicers, etc.
  
## Summary
This dashboard has four pages that includes glossary, and other dimensional analysis. These includes various visualizations that comprises of charts, and graphs to analyze the trend and find the growth potential. The filters will enhance the interactivity which allows the users to explore the data by various parameters. Below are the findings from the analysis.

1. Sales and Profitability: Total sales number are very promising with a year-on-year change (%) of 46.90%, which denotes the sales are increasing with strong numbers.
2. Product Performance: With total of 1861 products, Canon Imageclass 2200 Advanced Copier is the most selling product with the total sales of $61K in overall.
3. Customer Standing: With 793 total customers, Customer ID (SM-20320) is the top customer with the spending of $20K in overall.
4. Category Performance: With 3 total categories, Office supplies secures the first place with over 1K products in it.
5. Sub-category Performance: With 17 sub-categories, Phones stands in the first place with a total products of 276.
6. Order Value: With a total of 4922 orders, year 2018 has the most orders with the count of 1.7K orders.
7. Regional Performance: Among 4 regions, West region holds the most customer base of 681 in total, which is 27.4% of the total customers
8. State and City Performance: With a total of 49 states and 528 cities, California (state) and New York City (city) holds the first position with 570 and 349 customers respectively.
9. Customer Segmentation: With a total of 3 customer segments, Consumer is the segment that has the most products of 409 in total.
