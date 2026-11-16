# FinSight Financial Analytics – Project Methodology

## 1. Project Overview
This project analyses financial performance for 2024 and 2025 using Microsoft Power BI.

## 2. Data Preparation
Power Query was used to clean and prepare the financial data before loading it into the Power BI data model.

Key preparation activities included:
- Reviewing data types.
- Cleaning and transforming transaction data.
- Preparing dimension tables.
- Ensuring financial values were represented correctly.

## 3. Data Modelling
A star-schema model was implemented to organise the financial data.

The model includes:
- FactFinancialTransactions
- DimAccount
- DimDate
- DimBranch
- DimDepartment
- DimCostCentre

Active one-to-many relationships connect the dimension tables to the fact table.

## 4. DAX Calculations
DAX measures were developed to calculate and analyse:
- Total Revenue
- Cost of Sales
- Gross Profit
- Gross Profit Margin
- Operating Expenses
- Operating Profit
- Other Income
- Other Expenses
- Profit Before Tax
- Monthly and year-on-year performance

## 5. Report Development
The Power BI report contains six pages:
1. Executive Dashboard (Overview)
2. Revenue and Gross Profit
3. Operating Performance
4. Final Profitability
5. 2024 vs 2025 Performance Analysis
6. Profit & Loss Statement

## 6. Analysis Approach
The project compares the financial results for 2024 and 2025, examines monthly trends, identifies major expense categories and evaluates the effect of cost growth on profitability.

## 7. Reporting and Recommendations
Findings from the analysis were translated into a Word management report containing an executive summary, key findings and three strategic recommendations.

## 8. Tools Used
- Microsoft Power BI Desktop
- Power Query
- DAX
- Microsoft Word
- GitHub
