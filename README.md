# sql-challenge

I started by sketching out an ERD which I used for creating tables in pgadmin.Once imported, I checked that the tables were accurate and then imoprted CSV files into the tables of my Employees_DB. Once the dabase was complete, I checked each table and ran the requested queries.

Then, I imported my database to Pandas. 

First I created a histogram using the salaries table.



Then I merged the employees table with salaries table using the employee number.  I comibed this table with the tiles table. This required renaming the  title_id column to emp_title_column in order for the merge to be possible.

This final dataset I grouped by titles, calculated mean for the salaries per each title, and created a bar chart. 


