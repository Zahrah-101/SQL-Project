# SQL-PROJECT

ABOUT THE DATA

The data was imported from Kaggle Site. The dataset is a simple dataset of the compilation of salaries of different data science roles accross the US and Uk with repect to their various job types. The dataset contains 12 columns and 607 rows.

The colums make up the:
1. Work_year: The year the salary was paid.

2. Experience_level:	The experience level in the job during the year with the following possible values: EN Entry-level / Junior MI Mid-level / Intermediate SE Senior-level / Expert EX Executive-level / Director

3. Employment_type:	The type of employement for the role i.e PT for Part-time, FT for Full-time, CT for Contract and FL for Freelance.

4. Job_title	The role worked in during the year.

5. Salary:	The total gross salary amount paid.

6. Salary_currency:	The currency of the salary paid as an ISO 4217 currency code.

7. Salary_in_usd:	The salary in USD (FX rate divided by avg. USD rate for the respective year via fxdata.foorilla.com).

8. Employee_residence	Employee's primary country of residence in during the work year as an ISO 3166 country code.

9. Remote_ratio	The overall amount of work done remotely, possible values are as follows: 0 No remote work (less than 20%) 50 Partially remote 100 Fully remote (more than 80%).

10. Company_location:	The country of the employer's main office or contracting branch as an ISO 3166 country code.

11. Company_size:	The average number of people that worked for the company during the year: S less than 50 employees (small) M 50 to 250 employees (medium) L more than 250 employees (large)


DATA ANALYSIS USING SQL COMMANDS

After physcally viewing and making reserach on the collected dataset, it was quite obvious that the dataset is a simple, straightforward dataset with little to no errors. To further confirm this, the data was cleaned and analysed using the Microsoft SQL Server 2022 version. Various SQL commands were also used to view the dataset for duplicates, missing values and incorrect and inconsistent data. The entire dataset was queried and analysed for further comprehenshion of the dataset. 

The file containing the commands has been attached to this repository for further details.



DATA VISUALIZATION USING BOWER BI

To further visualise and tell a visual story of the salaries of the different IT roles in the companies, the cleaned data was analysed and visualised using the power BI tool.

The visualized document is attached the repository for detail view. 
