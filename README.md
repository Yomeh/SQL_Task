# SQL_Task
# TASK 1
# Introduction
SQL(Structured Query Language) is a type of language used to manage relational databases. It is used to query a collection of organized and structured data. In this session, I understood the various types of databases such as Relational and Non-Relational, emphasis was placed more on the relational databases as it would be the working database used. To use this database, the SQL Server Management System tool would be the working environment.

The first session of the SQL kicked off with introductions to what SQL is, followed by learning about databases, creating databases, creating and altering tables to adding constraints within the database.

# Skills Demonstrated
1. Database creation
2. Table creation and modification

# Objectives
- Create a database named student's record
- Create tables of Student info, Performance, and Health records within the database
- Add constraints to specific columns.
- Modify tables(Renaming and Dropping Columns)

# Creating Database
![Screenshot (39)](https://github.com/Yomeh/SQL_Task/assets/140501792/64f869de-e115-4435-b420-9400b9aabde6)
On the new query page in the SQL server window, to create a new database the syntax displayed in the image above was written and it resulted in the students_profile2 database displayed on the left-hand side of the image.

# Creating Tables

**Student Info**
![Screenshot (40)](https://github.com/Yomeh/SQL_Task/assets/140501792/0e412418-16c8-4d89-a864-e816e049d5aa)
To create this table, the syntax displayed in the image above was entered into the SQL server window. Each column name was entered followed by the data type to be entered into each column. For this table, the **PRIMARY KEY** constraint was used on the student id column to uniquely identify the column and prevent the column from having duplicates. The **NOT NULL** constraint was also added to the student id column to prevent the column from accepting null values, an **INT** data type was used for the Student id and Age column since we're only going to be inputting numbers/integers into these columns. The **VARCHAR** data type was used for the Gender, Name, and Subject columns because only text strings would be inputted into these columns. The **NOT NULL** constraint was also used on the Subject column to prevent the column from accepting null values.

**Health Records**
![Screenshot (41)](https://github.com/Yomeh/SQL_Task/assets/140501792/16f3803d-1b2b-4936-a27f-8ebc197c8617)
For this table, we made use of the **PRIMARY KEY** constraint to make the Student ID unique and prevent duplicates in the column. For the Height, Weight, and Student ID column the **INT** data type was used while the **VARCHAR** data type was used for the Blood Group column.

**Performance**
![Screenshot (42)](https://github.com/Yomeh/SQL_Task/assets/140501792/37b97b8a-07e0-4976-9bdd-bdb5fc997d0c)
The performance table had the following columns inputted into it; Student ID which an **INT** data type was used to represent the column, Score which also had the **INT** data type and finally the Grade column which was represented with a **VARCHAR** data type. The **DEFAULT** constraint was used for the Score column whereby if there isn't any value in the column it returns a default value which was set in the image above as 0.

# Modifying Table
**Renaming Column**
![Screenshot (43)](https://github.com/Yomeh/SQL_Task/assets/140501792/fcaa778e-629c-45b1-b84f-435c8cc03ae7)
The column name Subject from the Student Info table was to be changed from Subject to Course. To achieve this, we used the **ALTER TABLE RENAME** syntax but it didn't work on the SQL server so we used a different syntax displayed in the image above.

**Dropping a Column**
![Screenshot (44)](https://github.com/Yomeh/SQL_Task/assets/140501792/66d1abce-d15e-406d-8b92-e2d550ec0728)
To drop a column from the table, the ALTER TABLE table_name DROP COLUMN column_name syntax was used to drop the Age column from the students' info table.

# Conclusion
This task allowed me to demonstrate my knowledge of SQL syntax, using constraints, SQL data types, and the Alter function.
