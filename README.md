
# Gravity Books Data Warehouse Solution
## Overview
This repository contains the solution for creating a data warehouse ('gravity_books_dwh') for the Gravity Books company. The solution encompasses the creation of tables, ETL processes, OLAP cubes, and self-service BI reporting using PowerPivot or Power BI.

## Solution Components
### DDL Statements: Contains SQL scripts for table creation in the data warehouse.
### ETL SSIS Project: SSIS packages to extract data from the 'gravity_books' transactional database and load it into the data warehouse.
### OLAP SSAS Project: Tabular model developed using SQL Server Data Tools for creating cubes.
### PowerPivot/Power BI Files: Self-service BI reporting using Excel (PowerPivot) or Power BI Desktop.
## Steps to Set Up and Run
DDL Statements: Execute the SQL scripts in a compatible database environment to create the necessary tables.
ETL SSIS Project:
Open the SSIS project in Visual Studio.
Configure connections to the source ('gravity_books') and target ('gravity_books_dwh') databases.
Run the SSIS packages to populate data into the data warehouse.
OLAP SSAS Project:
Open the SSAS project in SQL Server Data Tools.
Design and deploy the tabular model to create cubes for analysis.
PowerPivot/Power BI:
Open the PowerPivot file in Excel or the Power BI file in Power BI Desktop.
Connect to the OLAP cubes created earlier.
Create reports and dashboards for analysis and insights.
