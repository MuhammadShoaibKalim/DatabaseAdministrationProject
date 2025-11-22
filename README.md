# Getting Started with MySQL

 <h4> What is a Database? </h4>
A database is a container that stores related data in an organized way. In MySQL, a
database holds one or more tables.

 <h5> Folder Analogy: </h5>

 - A database = a folder
 - A table = a file inside that folder
 - Rows in the table = content inside each file

 <h5> Excel Analogy: </h5> 

 -  A database = an Excel workbook
 -  Each table = a sheet inside the workbook
 -  Each row = a row inside an Excel sheet


Step 1: Create a Database
After creating the database, either:
Right-click it in MySQL Workbench and select “Set as Default Schema”, or

<h5>Use this SQL command:</h5>

```
 CREATE DATABASE startersql;
 USE startersql;
```
<h5> Step 2: Create a Table</h5>

Now we’ll create a simple users table:

This table will store basic user info.

<h5>Step 3: Drop the Database</h5>

You can delete the entire database (and all its tables) using:

Be careful — this will delete everything in that database.


