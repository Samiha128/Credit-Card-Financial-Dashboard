# Table of Contents

- [Overview of the Project](#overview-of-the-project)
- [repository-structure](#repository-structure)
- [Architecture of the Project](#architecture-of-the-project)
- [Value Added by This Project](#value-added-by-this-project)
- [Contact](#contact)
  ## Overview of the Project

This project focuses on analyzing financial data to create dashboards that provide detailed insights into customer consumption habits within the banking sector. The analysis aims to uncover a variety of trends and correlations to inform strategic decisions and improve service offerings.

Key areas of investigation include:

1. **Gender-specific Credit Card Usage:** Analyzing trends to understand differences in credit card usage patterns between genders. This includes examining the frequency of transactions, average transaction amounts, and preferred spending categories.

2. **Impact of Marital Status on Financial Behavior:** Investigating how marital status influences credit consumption patterns and financial decisions. This analysis will explore whether there are notable differences in spending behavior between married, single, and other marital status categories.

3. **Most Utilized Categories of Bank Cards:** Identifying which categories of bank cards (e.g., debit, credit, prepaid) are most frequently used by customers. This analysis will help prioritize service improvements and marketing strategies tailored to customer preferences.....................

   
   ## repository-structure
   


│   README.md
│
├── data
│   │   cc_add.csv
│   │   credit_card.csv
│   │   cust_add.csv
│   │   customer.csv
│
├── images
│   │   ETL Pipeline.png
│   │   data modeling.png
│   │   workflow of the project (dashboard).png
│
├── Queries
│   │   DAX queries.txt
│   │   SQL Query - Financial Dashboard Data.sql
│
├── dashboard
    │   credit_card.pdf
    │   customer.pdf
    │   customer.pbix
    │   dashboard.pdf


   ## Architecture of the Project

The architecture of this project involves several key steps to analyze and visualize financial data:

1. **Loading the Dataset into PostgreSQL:**
   - The project begins with importing the financial dataset into PostgreSQL

2. **Performing Transformations within PostgreSQL (SQL):**
   - Utilizing SQL queries, transformations are applied to the dataset within PostgreSQL. This includes cleaning the data, aggregating information, and preparing it for further analysis and visualization.

3. **Exporting Data to Power BI:**
   - After processing in PostgreSQL, the transformed data is exported to Power BI

4. **Applying Additional Transformations using DAX:**
   - Within Power BI, further transformations are implemented using Data Analysis Expressions (DAX).

5. **Creating Dashboards:**
   - Two primary dashboards will be developed:
     - **Customer Dashboard:**
     - **Credit Card Dashboard:**
       


       
## Workflow of the Project 

![workflow of the project (dashboard)](https://github.com/Samiha128/Credit-Card-Financial-Dashboard/assets/120471620/9f5559c8-c066-4c59-b8f0-e7f148ad2b88)

## ETL Pipeline

![ETL Pipeline](https://github.com/Samiha128/Credit-Card-Financial-Dashboard/assets/120471620/d7d3e430-1c75-410e-b18e-d14482ce8b9f)


## Customer Dashboard

![image](https://github.com/Samiha128/Credit-Card-Financial-Dashboard/assets/120471620/fba6418f-c42f-431c-a1a7-e90ac509734f)

## Credit Card Dashboard

![image](https://github.com/Samiha128/Credit-Card-Financial-Dashboard/assets/120471620/74b8f7a5-f8fe-4b37-b561-baa0a290b179)









