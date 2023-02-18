# Microsoft AdventureWorks Database Analysis and Visualization with PowerBI
## Setup requirement
- Data: Download the AdventureWorks sample databases from Microsoft Database link: (https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms). The database has 3 versions of backup files: OLTP, Data Warehouse and Lightweight. I chose 'AdventureWorksDW2019.bak' data for analysis and visualization.
- Query Editor: The query editing was done in Microsoft SQL Server Management Studio (SSMS). To connect and restore the databases to SSMS I followed the instruction provided in microsoft link as
- Visualization: The visualization was done using Microsoft Power BI.

## Business request and planning
- I followed the business request from the Manager Steve to build this analytics project. The key word is underlined for building this projet.
- After that planning is made based on the business demand and build the user stories as illustrated below
[user stories](https://github.com/rabbilbhuiyan/data-analyst-project-with-SQL-powerBI/blob/master/Business%20Request%20%26%20Planning/Business%20Demand%20Overview%20%26%20User%20Stories.pdf)

## Data cleansing and transformation 
- I first identified the necessary tables e.g Customer, Product, Calendar, InternetSales tables based on business request and user stories. Then using SQL statement I customized the tables and saved the results as CSV files. Finally, I splited them into dimension and fact tables. Example of SQL statement is:

![Product SQL](https://github.com/rabbilbhuiyan/data-analyst-project-with-SQL-powerBI/blob/master/Images/DIM_product.png)

## Data visualization
i) Entity realationship diagram model
![Data Model](https://github.com/rabbilbhuiyan/data-analyst-project-with-SQL-powerBI/blob/master/Images/Model%20Relations..png)

ii) Sales overview dashboard
![Sales overview](https://github.com/rabbilbhuiyan/data-analyst-project-with-SQL-powerBI/blob/master/Images/Sales%20Overview.png)

iii) Customer details dashboard
![Customer details](https://github.com/rabbilbhuiyan/data-analyst-project-with-SQL-powerBI/blob/master/Images/Customer%20Details.png)

iv) Product details dashboard
![Product details](https://github.com/rabbilbhuiyan/data-analyst-project-with-SQL-powerBI/blob/master/Images/Product%20Details.png)

**Note**: The PowerBI online publishing link isn't available right now because of subscription issues. I'll add that online link soon, so anyone can open it and interact with it as the whole thing is very dynamic.
