## One-click import of Excel to database
Summary: In our work, we often need to import Excel data into databases (such as MySQL, SQL Server, Oracle) for data analysis and processing. Usually we use database tools like Navicat or the Excel import function in the editor that comes with the database to manually import it. However, it is not easy for both professional and non-professional data processing personnel to correctly import an Excel file into a database. 
Now, through years of practice, we have solved various problems through the [ExcelToDatabase tool](https://github.com/ryjfgjl/ExcelToDatabase/blob/master/README.md), achieving one-click import of Excel into the database.

## Common Problems of Manually Importing Excel to the Database
1. The actual length of the data exceeds the set length of the data type and cannot be imported
2. Too many columns in Excel cannot create a table
The encoding format of the 3.csv file is incorrect, resulting in failure to import or importing messy code
4. The Excel header contains special characters and cannot be created
5. The file is too large, and manual import causes memory overflow or slow import
6. Too many files, too many manual import steps, very cumbersome
7. Excel does not have a header or multilevel header Manual import cannot handle it
8. The table name or field name exceeds the database limit and cannot be created
9. Blank cells, empty spaces at the beginning and end of data, duplicate data, missing data, data replacement, etc. Manual import cannot handle these situations
。。。


## One-click import
ExcelToDatabase is an automated tool that can import Excel files into a database in bulk.
Support for 6 common formats of Excel files (xls/xlsx/xlsm/xlsb/csv/txt) and 8 database types (mysql/oracle/sql server/postgresql/access/hive/sqlite/dameng).
Let's take an example of importing a product information table into a MySQL database.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/apd26wmf7y1wgg3lmb73.png)


Now, we can import it to the database with one click through the ExcelToDatabase tool.
Step 1: Create a new database connection
Click on the toolbar (New Connection) to select your database type.  Here, we will use MySQL as an example.  To create other database connections, please refer to the [ExcelToDatabase New Database Connection Guide](https://medium.com/r/?url=https%3A%2F%2Fgithub.com%2Fryjfgjl%2FExcelToDatabase%2Fwiki%2FDatabase-Connection-Guide).

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/k6nhek0tvix68q46ls9g.png)



Step 2: Add configuration

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ammd2aw1kvvoe51v85qi.png)



Step 3: Select the file to import and click "Start"

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/erwhv8uexha6nxtgimfl.png)



Finally, enter the database editor to view the import results

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/iy7m3r3ur5gu7v2anz0l.png)




## Introduction and Download of ExcelToDatabase

- [ExcelToDatabase - Automation tool for batch importing Excel files into database](https://github.com/ryjfgjl/ExcelToDatabase/blob/master/README.md)
