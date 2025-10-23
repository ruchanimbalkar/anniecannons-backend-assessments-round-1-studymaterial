# Create and Query a SQL Table

## Create a SQL Table

### Syntax :

Create table statement w/ optional table constraint and default value

> CREATE TABLE table_name ( column DataType TableConstraint DEFAULT default_value, another_column DataType TableConstraint DEFAULT default_value, … );

### Example :

Create a table called _employees_.
It will have 4 columns:

1. id
2. first_name
3. last_name
4. email
5. department

```sql
CREATE TABLE employees
( id INTEGER PRIMARY KEY,
first_name VARCHAR NOT NULL,
last_name VARCHAR NOT NULL,
email VARCHAR UNIQUE NOT NULL,
department VARCHAR NOT NULL);
```

Related [DB-Fiddle](https://www.db-fiddle.com/f/uxff4DFL22uWVbiZfGHkqn/11)

---

## INSERT INTO

### Syntax :

> INSERT INTO table_name(column, another_column, …)
> VALUES (value_or_expr, another_value_or_expr, …),
> (value_or_expr_2, another_value_or_expr_2, …),
> …;

### Example :

```sql
INSERT INTO employees (id, first_name,last_name, email, department)
VALUES
(213540, 'Chacha', 'Chaudhary', 'cchaudhary@yahoo.co', 'Marketing'),
(1, 'Champak', 'Masik', 'cmasik@rediff.in', 'Event Management'),
(214533, 'Chanda', 'Mama', 'cmama@gmail.com', 'IT');
```

Related [DB-Fiddle](https://www.db-fiddle.com/f/uxff4DFL22uWVbiZfGHkqn/11)

---

## SELECT

### Syntax :

> Select query for all columns
> SELECT \*
> FROM table_name;

### Example :

```sql
-- Select all the data in the employees table.
SELECT * FROM employees;
```

Related [DB-Fiddle](https://www.db-fiddle.com/f/uxff4DFL22uWVbiZfGHkqn/11)

### SQL Cheat sheet on [Codecademy](https://www.codecademy.com/learn/learn-sql/modules/learn-sql-manipulation/cheatsheet)
