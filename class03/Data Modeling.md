## Data Modeling

### nosql vs sql

**What type of database is the best fit for the complex query intensive environment?**

In a complex query-intensive environment, a relational database management system (RDBMS) is generally considered the best fit. RDBMSs are designed to handle structured data and provide powerful query capabilities through a structured query language (SQL).

**What type of database is the best fit for hierarchical data storage?**

For hierarchical data storage, a hierarchical database management system (HDBMS) or a document database would be the best fit.

**Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.**

When it comes to scalability, SQL and NoSQL databases have different approaches. Imagine you have a business that starts small but grows rapidly over time. You need a database that can handle more and more data and keep up with your increasing demands. This is where scalability becomes important

### sql modeling techniques

**Among data tables, what is a one-to-many relationship and how do we “relate” them?**

A one-to-many relationship in the context of data tables refers to a relationship between two tables where one record in the first table can be associated with multiple records in the second table, but each record in the second table is related to only one record in the first table.

**Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.**


Prior to designing your relational database, it might be useful to create a "diagram" of the database tables and their relationships.

**Explain the difference between a primary and foreign key.**

A primary key is a column or set of columns in a table that uniquely identifies each record or row in that table. It serves as a unique identifier for each entry and ensures that there are no duplicate values in the primary key column(s).

A foreign key is a column or set of columns in a table that refers to the primary key of another table. It establishes a relationship between two tables based on the values of the foreign key and the primary key.

### sql vs nosql

**How do we treat keywords and parameters differently in SQL syntax?**

Keywords are reserved words that have predefined meanings in SQL. They are part of the SQL language syntax and are used to define the structure and operations within SQL statements

Parameters, also known as placeholders or bind variables, are used to pass dynamic values into SQL statements. They act as variables that hold values that will be substituted during execution.

**Define normalization within the context of schemas and data.**

Normalization is a process in database design that involves organizing data in a structured and efficient manner by eliminating data redundancy and ensuring data integrity. It aims to reduce data duplication and inconsistencies while improving data storage efficiency and query performance.

**Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**

A one-to-one relationship is like a unique match, a one-to-many relationship is a parent-child relationship, and a many-to-many relationship involves multiple entities on both sides. Understanding these relationship types is important for organizing and representing data accurately in a database system.