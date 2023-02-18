# Microsoft AdventureWorks Database Analysis and Visualization with PowerBI
## Setup requirement
- Data: Download the AdventureWorks sample databases from Microsoft Database link: (https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms). The database has 3 versions of backup files: OLTP, Data Warehouse and Lightweight. I chose 'AdventureWorksDW2019.bak' data for analysis and visualization.
- Query Editor: The query editing was done in Microsoft SQL Server Management Studio (SSMS). To connect and restore the databases to SSMS I followed the instruction provided in microsoft link as
- Visualization: The visualization was done using Microsoft Power BI.

## Business request and planning
- I followed the business request from the Manager Steve to build this analytics project. The key word is underlined for building this projet.
- After that planning is made based on the business demand and build the user stories as illustrated below

## Data cleansing and transformation 
- I first identified the necessary tables e.g Customer, Product, Calendar, InternetSales tables based on business request and user stories. Then using SQL statement I customized the tables and saved the results as CSV files. Finally, I splited them into dimension and fact tables.

## Data visualization
i) Entity realationship diagram model
![Data Model](https://github.com/rabbilbhuiyan/data-analyst-project-with-SQL-powerBI/blob/master/Images/Model%20Relations.png)

