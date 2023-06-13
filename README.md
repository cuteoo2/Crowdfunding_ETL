# Crowdfunding_ETL


A collaborative project to build an ETL pipeline using Python, Pandas, and PostgreSQL for extracting, transforming, and loading crowdfunding data from Excel files into a relational database.

ETL (Extract, Transform and Load) data processing is an automated procedure that extracts relevant information from raw data, converts it into a format that fulfills business requirements and loads it into a target system.




- Instructions

The instructions for this mini project are divided into the following subsections:

Create the Category and Subcategory DataFrames
Create the Campaign DataFrame
Create the Contacts DataFrame
Create the Crowdfunding Database



- Features


Utilize Python and Pandas in order to:
Extract and transform crowdfunding and contact data from Excel files
Create and export Category, Subcategory, Campaign, and Contact DataFrames as CSV files
Utilize PostgreSQL in order to:
Design an ERD and table schema for the database
Create and populate PostgreSQL database tables



- Data


For our analysis, we have extracted and transformed data from the following datasets available in the Resources folder.

contacts.xlsx
crowdfunding.xlsx
Then, we loaded our transformed data into crowdfunding_db PostgreSQL database.

category.csv
subcategory.csv
contacts.csv
campaign.csv


- Outcome


In this project, we have demonstrated the ETL pipeline utilizing Python, Pandas, and a combination of both Python dictionary and regular expression techniques for data extraction and transformation. We were able to successfully generate four CSV files (category.csv, subcategory.csv, contacts.csv, campaign.csv) and used the data in these files to design an ERD as well as table schema, then loaded the data into PostgresSQL database (Crowdfunding_db) from the CSV files via dataframes.
