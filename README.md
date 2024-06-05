# Excel_Sales_And_Finance_Analytics

![sales and finance](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/311a4c20-9b2d-42d4-96e9-895c860266da)



# 📊 Excel: Mother of Business Intelligence - Sales and Finance Analytics Project  https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/blob/main/Sales%20and%20financial%20Report/Sales_and_finance_analysis_.pdf

Welcome to my GitHub repository, This repository includes comprehensive project focused on Sales and Finance Analytics, demonstrating my ability to handle real-time business requirements using advanced Excel techniques.

## Project Objective:
Expertise a comprehensive sales and financial report analysing AtliQ Hardware's market performance for the years 2019, 2020, and 2021, furnishing valuable insights for informed decision-making.

## Project Breakdown:
Sales Analysis: Conducted a comprehensive analysis, examining yearly trends, customer contributions, market segmentation, product performance, and divisional breakdowns to facilitate strategic decision-making. Finance Analysis: Developed key financial metrics and integrated them into a comprehensive Profit and Loss statement to enhance decision-making capabilities.


## 📈 Sales Analytics 
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
1. **Top 10 Products** top 10 products based on the percentage increase in their net sales from 2020 to 2021.

![top10](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/719eeb1d-c66b-492f-97a8-91eb492775c1)


   
2 **Division Report**: Generate a "Division" report to present the net sales data for 2020 and 2021, along with the growth percentage.

![dlevel](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/dbd54c4b-4777-49ef-b845-2917f25f5c4a)

   
3. **Top 5 and Bottom 5 Products** top 5 and bottom 5 in terms of quantity sold.

![topbottom](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/7e096725-d400-4c80-be30-e7c72e2d74e8)

   
4. **New Products Launched in 2021**  new products that Atliq began selling in 2021.
   
![newproduct](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/4f3531de-19fd-48db-be76-9ce01e9140d6)


   
5. **Top 5 Countries**  top 5 countries in terms of net sales in 2021.

![top5](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/082a51c8-6afe-4515-bab5-efe61abe5bf1)



## 📊 Finance Analytics

![finance](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/b9ecb976-2acc-4ff4-8ada-df216e78b6aa)

## Finance Analytics Project Highlights:
## Understanding P&L Statements:
Learned the significance of Profit and Loss (P&L) statements in organizational financial health.
## COGS and Gross Margin:
Gained in-depth knowledge of Cost of Goods Sold (COGS) and how to calculate Gross Margin and Gross Margin Percentage.
## Data Modeling in Power Pivot:
Integrated financial data into the data model using Excel Power Pivot.
## DAX Formulas:
Created DAX formulas to compute Gross Margin and Gross Margin Percentage accurately.
## Report Creation:
Developed comprehensive P&L statements by fiscal year and fiscal month, enabling detailed financial analysis.


## SOME DAX-FORMULAS TO FIND THE P & L STATEMENT BY FISCAL YEAR AND FISCAL MONTH
1. **COGS** : SUM(fact_sales_monthly[total_cogs])
2. **Gross Margin** : [Net Sales]-[COGS]
3. **GM%** : DIVIDE([Gross Margin). [Net Sales].0)

**Business Reports Created:**
1. **P & L Statement by market**

![PLBYMARKET](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/1b3ef558-e2e4-4f4d-a7f5-5c4612b11728)
   
2. **GM% By Quarters**

![GMBYQ](https://github.com/Akshay2515/Excel_Sales_And_Finance_Analytics/assets/126151845/f819675d-e958-48d8-ab6f-ebc776f710cc)

## 🛠️ Tools and Technologies Used
1. **Excel**: Advanced features including Power Pivot and Power Query
2 **DAX**: Formulas for data analysis and reporting
3 **Power Query**: For ETL processes and data cleaning
