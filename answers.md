1.Components of a DBMS
Database Engine: Manages data storage, retrieval, and manipulation. It ensures data consistency and integrity.
Query Processor: Translates user queries into instructions that the DBMS can execute.
Database Schema: Defines the logical structure of the database, including tables, relationships, and constraints.
Transaction Management: Ensures database transactions are executed in a safe, consistent, and reliable manner.
Data Dictionary: Stores metadata, such as table definitions, column types, and constraints.
User Interface: Allows users to interact with the DBMS via graphical interfaces or command-line tools.


2.What is a Relational Database?
A relational database stores data in structured tables with predefined relationships. Each table has rows (records) and columns (fields), and data is organized based on relationships defined by keys.

Examples:
MySQL
PostgreSQL
Microsoft SQL Server
Oracle Database

3.Three Classifications of SQL
  a)Data Definition Language (DDL):

  Used to define the structure of the database.
  Examples: CREATE, ALTER, DROP.
  Purpose: Define and modify schema elements.
  
  b)Data Manipulation Language (DML):

  Deals with data manipulation and retrieval.
  Examples: SELECT, INSERT, UPDATE, DELETE.
  Purpose: Work with the data stored in the tables.

  c)Data Control Language (DCL):

  Manages permissions and access to the database.
  Examples: GRANT, REVOKE.
  Purpose: Control user access and security.

4.Difference Between a Primary Key and a Foreign Key
  a)Primary Key:

  Uniquely identifies each record in a table.
  Must be unique and cannot contain NULL values.
  
  b)Foreign Key:

  Establishes a relationship between two tables.
  References the primary key in another table and can have duplicate or NULL values.

5.What is an Entity-Relationship Diagram (ERD)?
  An ERD is a visual representation of the entities (objects) in a database, their attributes, and the relationships between them. It helps design and model a database's structure before implementation.

6.Advantages of Relational Databases
  Data Integrity: Maintains accuracy and consistency of data through constraints.
  Flexibility: Easy to modify and scale as data requirements evolve.
  Security: Allows implementation of user-specific access controls.
  Ease of Use: Uses structured query language (SQL) for efficient data management.

7.Four Types of Data Types Used to Store Data in Tables
  Integer: Stores whole numbers (e.g., INT, BIGINT).
  Character: Stores text (e.g., CHAR, VARCHAR).
  Date/Time: Stores dates and times (e.g., DATE, DATETIME).
  Decimal/Float: Stores precise or approximate decimal values (e.g., DECIMAL, FLOAT).

8.Purpose of a Database Management System (DBMS)
  The DBMS provides a framework for storing, managing, and retrieving data efficiently while ensuring:
  Data Integrity and Security.
  Concurrent Access for multiple users.
  Data Independence from applications.
  Backup and Recovery capabilities.






