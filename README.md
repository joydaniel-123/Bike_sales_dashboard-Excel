# Bike Sales Dashboard - Excel
This project showcases a Bike Sales Dashboard built using Excel for data cleaning ,transformation and data visualization.

![Bike_Sales - Excel](https://github.com/joydaniel-123/Bike_sales_dashboard-Excel/blob/main/Asset/WhatsApp%20Image%20bike.jpg?raw=true)

## Table of Contents:

- [Problem Statement](https://github.com/yogeshkasar778/PWC_task_2-Customer_Churn_Retension_dashboard/edit/main/README.md#problem-statement-)
- [Datasource](https://github.com/yogeshkasar778/PWC_task_2-Customer_Churn_Retension_dashboard/edit/main/README.md#datasource-)
- [Data Preparation](https://github.com/yogeshkasar778/PWC_task_2-Customer_Churn_Retension_dashboard/edit/main/README.md#data-preparation)
- [Data Analysis](https://github.com/yogeshkasar778/PWC_task_2-Customer_Churn_Retension_dashboard/edit/main/README.md#data-analysis-dax)
- [Data Visualization (Dashboard)](https://github.com/yogeshkasar778/PWC_task_2-Customer_Churn_Retension_dashboard/edit/main/README.md#data-visualization-dashboard)
- [Insights](https://github.com/yogeshkasar778/PWC_task_2-Customer_Churn_Retension_dashboard/edit/main/README.md#insights)
- [Recommendation](https://github.com/yogeshkasar778/PWC_task_2-Customer_Churn_Retension_dashboard/edit/main/README.md#recommendation)

## Problem Statement :

The purpose of this task is to:

- Create a dashboard for the sales manager reflecting the KPIs, findings, and include suggestions on what needs to be changed to improve bike sales.
- Write a short report to the sales team explaining the findings and include recommendations on what needs to be adjusted to boost sales.
- Identify customers who have not purchased bikes based on income, marital status, and education levels.
- Analyze customer purchase patterns based on services such as commute distance, age bracket, gender, occupation, and region.                                               - Provide customer demographic and purchase information: average income, marital status, education level, occupation, region, and purchase history.
- Include demographic insights about customers: gender, age bracket, and regional distribution to target marketing efforts effectively.

## Datasource :

Dataset used for this task was [Bike sales dataset](https://github.com/joydaniel-123/Bike_sales_dashboard-Excel/blob/7f7fa81b20af8ab224fff78705947e0cdb81478d/Bike%20sales%20dashboard.xlsx)

## Data Preparation:

Bike sales  is give table named:

- `Bike_buyers` which has `13 columns and 1026 rows` which the source table
- `working_sheet` which has `14 columns and 1000 rows` which the staging table

Data Cleaning for the dataset was done in the power query editor as follows:

- Imported CSV dataset into Excel for analysis.
- Removed duplicates and handled missing values.
- Reviewed data distribution and key variables.
- Added “Marital Status” and “Age Bracket” columns.
- Used VLOOKUP and IF statements in “Working Sheet,” created “Master Sheet” with gender codes.

## Data Analysis :
functions used in data analysis are:

- vlookup function for marital status full : `=VLOOKUP(B2,Table1[#All],2,FALSE)`
- IF function for Age bracket  : `=IF(L2>54,"Old",IF(L2>=31,"Middle age","Adolescent"))`
- Evaluated demographics from “Master Sheet” and other categories.
- Built pivot tables for dashboard visuals (bar, line, pie charts).

## Data Visualization (Dashboard):

Data visualization for the data analysis  was done in Microsoft Excel:

Dashboard: [View Dashboard](https://github.com/joydaniel-123/Bike_sales_dashboard-Excel/blob/08b6a3ad52eb521b2a6d7bd780fec82258bd3d02/Bike%20sales%20dashboard.xlsx)

Shows visualizations from Bike_sales analysis:

| Bike sales dashboard |
| ----------- |
|![Bike sales ](https://github.com/joydaniel-123/Bike_sales_dashboard-Excel/blob/main/Asset/screnshoot%20dash.PNG?raw=true)|


## Insights:

As shown the data Visualization, It can be deduced that:

- Married customers $60,000.00 and those with college education $54,000.00-$52,000.00 have higher incomes and potential buying power.
- Clerical, management, and professional roles show higher bike purchase counts.
- Midwest region leads bike purchases.
- Middle-aged customers are the most likely buyers.

## Recommendation:

- Focus marketing on middle/high-income, married, and college-educated customers.
- Target 0-2 mile commute customers with tailored campaigns.
- Promote to middle-aged and professional occupations.
- Boost Midwest region marketing.
- Offer incentives for longer commute customers.

---












