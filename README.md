# sql_commands
MySQL Commands
1. SELECT — extracts data from a database
SELECT column_name
FROM table_name;

SELECT statements fetch data from a database.

2. UPDATE — updates data in a database
UPDATE table_name
SET some_column = some_value
WHERE some_column = some_value;

UPDATE statements allow us to edit rows in a table.

3. DELETE — deletes data from a database
DELETE FROM table_name
WHERE some_column = some_value;

DELETE statements remove rows from a table.

4. INSERT INTO — inserts new data into a database
INSERT INTO table_name (column_1, column_2, column_3)
VALUES (value_1, ‘value_2’, value_3);

INSERT statements add a new row to a table.

5. CREATE DATABASE — creates a new database
CREATE DATABASE databasename;

CREATE DATABASE statements create a new SQL database.

6. ALTER DATABASE — modifies a database
ALTER DATABASE database_name
[COLLATE collation_name ]

ALTER DATABASE statements change the characteristics of a database.

7. CREATE TABLE — creates a new table
CREATE TABLE table_name (
column_1 datatype,
column_2 datatype,
column_3 datatype
);

CREATE TABLE statements create a new table in the database.

8. ALTER TABLE — modifies a table
ALTER TABLE table_name
ADD column_name datatype;

ALTER TABLE statements add, delete, or modify columns in an existing table.

9. DROP TABLE — deletes a table
DROP TABLE table_name;

DROP TABLE statements drop an existing table in a database.

10. CREATE INDEX — creates an index
CREATE INDEX index_name
ON table_name (column_name1, column_name2…);

Index statements create on existing tables to retrieve the rows quickly.

11. DROP INDEX — deletes an index
ALTER TABLE table_name
DROP INDEX index_name;

DROP INDEX statements delete an index in a table.

Thank you for reading.
