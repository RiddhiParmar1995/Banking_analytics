# Banking_analytics

### Project Overview

This data analysis project aims to provide insights into the bank loan and bank credit - debit overall performances . By analyzing various aspects of the bank data , we seek to identify  Total loan , Total amount funded , Total interst , state wise performance , branch wise performance , Total Revenue etc,.

### Data Sources 
 The Primary dataset used for this anaysis is the "Bank Data Analystics.csv" file, containing detail bank operations .

 ### Tools

  - Excel - Data Cleaning [Download here](https://microsoft.com)
  - My SQL - Data Analysis
  - Power BI - Creating reports
  - Tableau - Creating reports

### Data Cleaning/Preparation

In the initial data preparation phase ,  we performed the following tasks :
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the banking data to answer key questions , such as :

 - What is the total loan amount funded?
 - what is the total revenue?
 - Disbursement trend ?

   ### Data Analysis

   Include some interesting code worked with

   ```sql
   select concat(round(sum(`funded Amount`) / 1000000, 2), 'M') AS
   `Total Loan Amount funded`    from banking_data;
   ```

   ### Results
   

  

   

   

   
