# Inventory Data - Dashboard

## Problem Statement

This dashboard helps understand production data better. So in this particular project, I have basically represented six KPIs on a two page power BI report.

So the first page represents the KPIs such as average demand per day, average availability per day, total supply shortage.

And on the second page we have total profit, total loss and average daily loss.




### Steps followed 

- Step 1 : Understanding the test environment data and requirements.
- Step 2 : Open SQL Server and create a new database test_environment and import the data in SQL Server, dataset is a csv file.
- Step 3 : Apply joins in SQL Server to prepare the data to be used in reporting purpose. 
- Step 4 : Open Power BI Desktop and import the data from test_environment.
- Step 5 : Create the DAX Measures & KPIs for page 1, which includes( average demand per day, average availability per day, total supply shortage).
- Step 6 :  Create the DAX Measures & KPIs for page 2, which includes(total profit, total loss and average daily loss).
- Step 7 : Since the data got updated, import the data into Production Environment In SQL Server. 
- Step 8 : Data cleaning in SQL Server and transitioning the report from test environment to production environment.
- Step 9 : After data cleaning open Power BI Desktop and uder Home ribbon click on Transform Data -> and select change data source. This will add new data to report visual without affecting the KPIs and Measures.
- Step 9 : Create Workspace in Power Bi Service and publish SQL Server Data Source report.
           
## DAX Formulas used for KPIs
![DAX Formulas](https://github.com/user-attachments/assets/91f418a4-901a-4952-90bd-469fcf8a834c)
