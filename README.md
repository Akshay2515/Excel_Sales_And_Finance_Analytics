# Excel_Sales_And_Finance_Analytics

![sales and finance](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/311a4c20-9b2d-42d4-96e9-895c860266da)



# 📊 Excel: Mother of Business - Sales and Finance Analytics Project
Welcome to my GitHub repository, This repository includes comprehensive project focused on Sales and Finance Analytics, demonstrating my ability to handle real-time business requirements using advanced Excel techniques.

## Project Objective:
Expertise a comprehensive sales and financial report analysing AtliQ Hardware's market performance for the years 2019, 2020, and 2021, furnishing valuable insights for informed decision-making.

## Project Breakdown:
Sales Analysis: Conducted a comprehensive analysis, examining yearly trends, customer contributions, market segmentation, product performance, and divisional breakdowns to facilitate strategic decision-making. Finance Analysis: Developed key financial metrics and integrated them into a comprehensive Profit and Loss statement to enhance decision-making capabilities.


## 📈 Sales Analytics Project
## Key Components:

## ETL Process:
Extracted, transformed, and loaded data using Power Query to connect data from diverse sources.
## Data Cleaning:
Ensured data accuracy and usability by identifying and correcting inaccuracies in Power Query.
## Report Planning:
Designed business reports, focusing on components such as net sales, year, division, country, and region.
## Data Modeling:
Connected various datasets by establishing relationships and understanding fiscal year concepts.

![data model](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/2f371aee-8a8f-4ad8-a136-ca2503ffabf8)



## Customer Net Sales Performance Report:
Created using Pivot Tables and DAX formulas like CALCULATE().
## Conditional Formatting:
Applied to highlight important data, identify trends, and improve data readability.
## Market Performance Reports:
Developed reports to analyze market-wise performance vs. targets.


## SOME DAX-FORMULAS USED TO FIND THE CUSTOMER NET SALES PERFORMANCE AND MARKET PERFORMANCE vs. TARGET
1. **Net Sales** : SUM(fact_sales_monthly[net_sales_amount])
2. **Net Sales 2019** : CALCULATE ([Net Sales], dim_date [FY year] = "2019")
3. **Net Sales 2020** : CALCULATE ([Net Sales], dim_date [FY year] = "2020")
4. **Net Sales 2021** : CALCULATE ([Net Sales], dim_date [FY year] = "2021")
5. **2021 vs 2020** : DIVIDE([Net Sales 2021]. [Net Sales 2020).0)
6. **2021-Target** : [Net Sales 2021]-[Target 21]
7. **2021-Target%** : DIVIDE([2021-Target]. [Net Sales 2021].0)


**Business Reports Created:**
1. **Top 10 Products** by Percentage Increase in Net Sales (2020-2021)

![top10](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/719eeb1d-c66b-492f-97a8-91eb492775c1)


   
3. **Division Report**: Net sales data for 2020 and 2021 with growth percentages.
4. **Top 5 and Bottom 5 Products** by Quantity Sold
5. **New Products Launched in 2021** by Atliq
6. **Top 5 Countries** by Net Sales in 2021
