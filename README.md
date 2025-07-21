# Banking_analytics

## Table of Contents

 - [Project Overview](#project-overview)
 - [Data Sources](#data-sources)
 - [Tools](#tools)
 - [Data Cleaning/Preparation](#data-cleaning/preparation)
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Data Analysis](#data-analysis)
 - [Results](#results)
 - [Recommendations](#recommendations)
 - [Limitations](#limitations)
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

   The analysis results are summarized as follows:

   1.The bank's credit amount is more than bank's debit amount so that bank is in growth.
   
   2.The bank has actively collected it's interst that is around 155 Million.
   
   3.The highest loan is taken by customer is home loan and is about to fully paid.

   ### Recommendations

   Based on the analysis , we recommend the following actions:
   - There are very less transactions occure in the month of december so bank should give some offer to maximize the transaction frequency.
   - There are 20.43K high-risk transactions which need further investigation.
   - The Delinquency Rate is 10.84% (7,106 out of 65,535 loans). This reflects a moderate credit risk and serves as a warning that the bank should closely monitor borrowers loan statuses.
  
   ### Limitations

     We don't have exact amount to calculate the high risk transactions so it became more difficult to find accurate high risk transactions.

   

  

   

   

   
