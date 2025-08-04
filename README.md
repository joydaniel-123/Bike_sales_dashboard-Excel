# Bike_sales_dashboard-Excel
This project showcases a Bike Sales Dashboard built using SQL for data cleaning and transformation, and Power BI for data visualization.

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

Dashboard: [View Dashboard](https://www.novypro.com/project/yogeshkasar97-1)

Shows visualizations from Customer Retention analysis:

| Customer Churn |
| ----------- |
|![PWC Task 2-Customer Churn Retenstion_page-0002](https://user-images.githubusercontent.com/118357991/229330706-03af1d41-a7e3-4449-8867-55322ecdf371.jpg)|

| Customer Risk |
| ----------- |
|![PWC Task 2-Customer Churn Retenstion_page-0003](https://user-images.githubusercontent.com/118357991/229330924-5b82f4ab-8326-41f0-b001-e56eb264d3ba.jpg)|

| Services |
| ----------- |
|![PWC Task 2-Customer Churn Retenstion_page-0004](https://user-images.githubusercontent.com/118357991/229330958-68b013f5-d013-4de6-a4f7-6a2500823de0.jpg)|

## Insights:

As shown the data Visualization, It can be deduced that:

- Customers on the Two-Year contract, have been with the company for long, while most of the customers on Month-to-Month contract joined the company.
- The company is at risk of losing recently joined customers. based on the results from analysis.. if they decided to month-to-month contract.
- 7043 customers are at the risk of churn. and The churn rate is 27%  and yearly charges is $16.06M charges. and Monthly Charges is $456.12K monthly charges.
- 2955 tech tickets were opened and 3632 admin tickets were opened.
- Most of the churned customers  did not sign up for Online Security and tech support and  also did not sign up for Phone Services.
- It a lot of customers had an issue with Fiber Optic . Up to 42% of the customers churned were using Fiber Optic as their Internet Services.

## Recommendation:

- The Company could try convincing customers to subscribe to One-Year and Two-Year contract. The contract are not favorable to customers  as they tend to pay more monthly.
- Giving the discount to customers based on the some specific tasks is also good wat retaining them, specially those month-to-month contract.
- From analysis majority customers who churned did not sigh up for Online Security and Tech Support. These are the important services that customers should customers signup for. The company should educate customers  on the benefits of signing up for these services.
- Increase sale of 1 and 2 year contract by 5% each and Yearly increase of automatic payments by 5%.

---












