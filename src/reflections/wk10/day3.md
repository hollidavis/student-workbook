# Day 3 | Connecting to A MySql Database

## Afternoon Code
+ [Knight's API](https://github.com/hollidavis/knightsapi)

## Daily Journal:

**In a SQL table, what is the difference between information in a row and information in a column?**

+ The information in a row is the information that is stored for a specific object that is added to the table. The column are the types of information that is listed for every object that is added to the table.

**Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.**

+ CREATE TABLE characters( id int NOT NULL, name VARCHAR(255) NOT NULL, age int, description VARCHAR(255), ); By using this set of code, it would create the sql table with the columns for each of the specified values.

**What is the difference between the following statements:**
+ DELETE FROM table_name - Deletes a set of data from the table
+ DROP TABLE table_name - Deletes the entire table and all it's data