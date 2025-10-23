# SQL Datatypes

## Some common data types (VARCHAR, BOOLEAN, SERIAL , etc.)

    1. SERIAL
    2. VARCHAR
    3. TEXT
    4. BOOLEAN
    5. INTEGER

### [Datatypes in postgreSQL](https://www.geeksforgeeks.org/postgresql/postgresql-data-types/)

## Constraints for creating tables (PRIMARY KEY, NOT NULL, UNIQUE)

### Column Constraints

#### Column constraints are the rules applied to the values of individual columns:

- **PRIMARY KEY** constraint can be used to _uniquely_ identify the row.
- **UNIQUE** columns have a different value for every row.
- **NOT NULL** columns must have a value.
- **DEFAULT** assigns a default value for the column when no value is specified.
- Note : _There can be only one PRIMARY KEY column per table and multiple UNIQUE columns._

Courtsey : [Codecademy](https://www.codecademy.com/learn/learn-sql/modules/learn-sql-manipulation/cheatsheet)
