# Class 04 Reading

### nosql vs sql

1. What type of database is the best fit for the complex query intensive environment?
    [The Geek Stuff - SQL vs NoSQL Database Differences Explained](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
      - SQL

2. What type of database is the best fit for hierarchical data storage?
      - NoSQL


3. Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.
      - You can increase the amount of space available in a SQL server by increasing the power and memory of the server.
      - In order to increase the amount of space for NoSQL, you need to add more servers to the database infrastructure.


### sql modeling techniques

1. Among data tables, what is a one-to-many relationship and how do we “relate” them?
    [Essential SQL - Data Modeling](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)
      - In a One to Many Relationship a record from one table is related to zero, one or many of the records of another table.
      - This class (401d51) can be compared to that: one Code Fellows instructor is "related" to many Code Fellows students  

2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
      - Draw a diagram


3. Explain the difference between a primary and foreign key.
      - Primary keys uniquely identify each row in a table
      - Foreign Key is a column or set of columns that match primary key in another table 

## Videos

### sql vs nosql

1. How do we treat keywords and parameters differently in SQL syntax?
    [SQL vs NoSQL or MySQL vs MongoDB](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
      - KEYWORDS are to be capitalized
      - Parameters are lowercase

2. Define normalization within the context of schemas and data.
      - Ensure how we fetch data fits into that table, even with missing data

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
    - One-to-One: a record in one table is related to one record in another table
    - One-to-Many: a record in one table can be related to multiple records in another table
    - Many-to-Many: multiple records on one table can be related to multiple records on another table  


## Bookmark and Review

### sequelize api

## Reflection

1. What are your learning goals after reading and reviewing the class README?
    - Gain better understanding of actually writing CRUD and wiring everything up correctly