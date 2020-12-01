# Soccer_Analysis

## Stepwise Implementation of the Project

Step 1: Importing the packages: numpy, pandas, sqlite3, matplotlib

Step 2: Creating the connection to the database using sqlite3 package and inserting queries to see what tables we have.

Step 3: The query that we have used is checking for list of countries. In order to display all the columns, I have used '*'.

Step 4: The next query used is to connect two tables namely leagues and their country. The two tables are connected using their unique id also called as Primary key.

Step 5: The next query is to print list of teams. The 'Order by' function sorts the 'team_long_name' column in ascending order. NOTE: if you mention desc in your code, it would sort in descending order.

Step 6: In the next query, I have used particular columns for which exact column names are mentioned. 'AS' after the column name depict the alias name (i.e. the name that will appear in the output display). 'WHERE' is used to put condition, 'ORDER' is used to sort the dates in ascending order.

Step 7: Here, additionally I have used 'avg','sum' method. There is standard rule for writing functionality. The sequence is WHERE, GROUP, HAVING, ORDER.

Step 8: I have used subqueries here as there is no direct connection to the table. 
