# CrowdFunding ETL 

## Project Overview
For the ETL mini project, you will work with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, you'll create four CSV files and use the CSV file data to create an ERD and a table schema. Finally, you’ll upload the CSV file data into a Postgres database.

Since this is a one-week project, make sure that you have done at least half of your project before the third day of class to stay on track.

Although you and your partner will divide the work, it’s essential to collaborate and communicate while working on different parts of the project. Be sure to check in with your partner regularly and offer support.

## Pre-requisites
- Python libraries(numpy, pandas, json) PgAdmin and SQL.
  -QuickDBD for ERD
  
https://app.quickdatabasediagrams.com/#/d/62QQg5

## Project Pipeline: 
![image](https://github.com/Mohammed-a-ali01/Crowdfunding_ETL-/assets/81397577/b64fa697-7b11-4f2f-85c5-106a035e1e74)

## Main Question
Build an ETL pipeline using python and pandas to extract and transform data. An ERD will also be used to showcase the relations between entites.

### Main Data Set:
- Name: crowdfunding and contacts
- Source: Given (UTOR)
- Column examples: crowdfunding: 'cf_id', 'contact_id', 'company_name', contacts: 'contact_id', 'first_name', 'last_named', 

### Data Cleaning/Preparation:
- Using our crowdfunding files we are able to create two seperate csv's for category and sub-categories.
- We have also created and transformed the campaign dataframe by renaming and fulfilling the requirements needed
- The contacts dataframe was transformed to meet a new formatted criteria and look more organized, with 'contact_id', 'first_name',  'last_name' and 'email'
  
## ERD 
The ERD includes the relationships that are present between contacts, category, campagin and subcategory. We use this to build our schema and then create our tables in sql to show the required output.
![ERD](https://github.com/Mohammed-a-ali01/Crowdfunding_ETL-/assets/81397577/0af5e87a-af8f-4952-bce3-b9ea9b9078d0)

## SQL
- As for our SQL queries we have simply included a screenshot of each new file (category, subcategory, contacts, campagin) and shown that the necessary data is included.

## How to Run
- Download the repository.
- All files should be fully functional.


## Project Execution
- Mohammed Ali
- Isabel Angwah

