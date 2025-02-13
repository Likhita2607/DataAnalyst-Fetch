# DataAnalyst-Fetch Assessment

# Repository Overview:
This repository outlines the process of cleaning unstructured data, generating actionable insights, and addressing key business questions as part of Fetch Assessment.In this exercise I used Python for Exploratory Data Analysis, Microsoft SQL and Power BI for answering business questions and generating insights in stakeholder communication email. 

The steps and methodologies employed to clean the data and extract meaningful insights are detailed below.

# Exercise Assessment:
## First: explore the data
In this section we were asked to review the given unstructured csv files addressing the data quality issues and challenging issues in the data with supporting code.

After extracting the unstructured CSV data into normalised data frame in python, I have noticed quite a few data quality issues as indicated in the referenced file.

Data Description and Quality Analysis is found from Reference: **FETCH_Data_Analysis.pdf**

The supporting code to find all these analysis is derived from Reference : **FETCH_EDA.ipynb**

## Second: provide SQL queries:
I first installed Microsoft Sql Server Management Studio 2014 and set up my local server. I also installed Microsoft ACE OLEDB 12.0 drivers to load data from csv into sql table.

I then imported excelfiles generated from .ipynb file given into master database and created tables for each of the files by clicking on Tasks-> Import Data. Then the SQL Server Import Wizard opens up to create a new destination table and then edit the mappings to load data from excel files.

After successful loading of data into master database, I have written the atached SQL queries (in MS SQL) for business questions given.

I have also done the same analysis in Power BI and attached the results in the PDF below. I have imported datasets into Power BI, transformed them in Power Query editor by adding few calculated columns (Customer Age, Customer Account Age, Generation), measures (YOY%) using DAX and generated visuals for the given business questions.

Reference : **FETCH SQL QUERIES.pdf**

## Third: communicate with stakeholders :
My thoughts regarding the questions given above and communicating them to Stakeholders through email can be found in Reference : **FETCH_StakeholderCommunication.pdf**
