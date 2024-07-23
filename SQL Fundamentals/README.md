# SQL Fundamentals

# What is SQL?

SQL stands for Structured Query Language, and it is the standard language for dealing with relational databases. SQL is used to perform tasks such as updating data on a database, or retrieving data from a database. Some common SQL commands include SELECT, INSERT, UPDATE, DELETE, CREATE, and DROP.

# What is a Query?

A query is a request for data or information from a database. Queries are written in SQL and can be used to search, filter, and retrieve specific data from one or more tables. For example, a SELECT query can be used to fetch data from a database based on certain criteria.

### The SELECT Statement

The SELECT statement is used to fetch data from a database. It allows users to specify the columns they want to retrieve and the conditions that the data must meet. For example:

```sql
SELECT column1, column2
FROM table_name
WHERE condition;
```

### Example 1

We have the table `student`. We can list all the elements with the following statement:

```sql
SELECT *
FROM student;
```

Output:

![Untitled](SQL%20Fundamentals%206e51d45982714cf796fdc05947d0e617/Untitled.png)

### Example 2

If we have only the first names and IDs of all the students, we can put:

```sql
SELECT firstname
FROM student;
```

Output:

![Untitled](SQL%20Fundamentals%206e51d45982714cf796fdc05947d0e617/Untitled%201.png)

# Imperative vs Declarative

In SQL, the language is declarative, meaning it specifies what data to retrieve rather than how to retrieve it. This contrasts with imperative programming languages, which require the programmer to explicitly define the sequence of operations to perform.