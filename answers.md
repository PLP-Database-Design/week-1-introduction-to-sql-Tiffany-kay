## Assignment Answers

#### 1. State and Explain the components of a DBMS(Database Management System)
1. **Database Engine**: The core service for accessing and processing data. It provides an interface to the physical data storage and facilitates CRUD (Create, Read, Update, Delete) operations on the data.
2. **Database Schema**: The structure of the database that defines how data is organized. It includes tables, fields, relationships, views, indexes, and other database objects.
3. **Query Processor**: Interprets and executes database queries written in SQL. It optimizes query execution to improve performance.
4. **Transaction Management**: Ensures that all database transactions are processed reliably and adhere to ACID (Atomicity, Consistency, Isolation, Durability) properties.
5. **Storage Manager**: Manages how data is stored, retrieved, and updated on the storage medium. It handles file storage, data blocks, and buffering.
6. **Database Administrator Tools**: Provide a set of utilities for managing and maintaining the DBMS, including backup, recovery, and monitoring tools.

#### 2. What is a relational database? Give 4 examples.
A **relational database** is a type of database that stores and provides access to data points that are related to one another. 
Relational databases use a structure that allows users to identify and access data in relation to another piece of data in the database, 
typically through tables with rows and columns.

**Examples:**
1. **MySQL**
2. **PostgreSQL**
3. **Oracle Database**
4. **Microsoft SQL Server**

#### 3. State and Explain three classifications of SQL?
1. **DDL (Data Definition Language)**: Commands that define the structure of the database, such as creating, altering, and dropping tables and indexes. Examples include `CREATE`, `ALTER`, `DROP`.
2. **DML (Data Manipulation Language)**: Commands that are used for data manipulation within the database. This includes inserting, updating, deleting, and retrieving data. Examples include `INSERT`, `UPDATE`, `DELETE`, `SELECT`.
3. **DCL (Data Control Language)**: Commands that deal with the rights, permissions, and other controls of the database system. Examples include `GRANT`, `REVOKE`.

#### 4. What is the difference between a Primary Key and a Foreign Key?
- **Primary Key**: A unique identifier for a record in a table. Each table can have only one primary key, and it cannot contain null values. It ensures that each record within the table can be uniquely identified.
- **Foreign Key**: A field (or collection of fields) in one table that uniquely identifies a row of another table. The purpose of the foreign key is to maintain referential integrity between the two tables. It allows links between records in different tables.

#### 5. What is an Entity-Relationship Diagram?
An **Entity-Relationship Diagram (ERD)** is a visual representation of the entities within a system and the relationships between those entities. It is a key tool in database design and helps in understanding the structure and constraints of the data.

#### 6. What are the advantages of relational databases?
1. **Data Integrity**: Ensures accuracy and consistency of data through constraints and keys.
2. **Flexibility**: Easy to modify schema without affecting existing data.
3. **Data Security**: Provides mechanisms to control access to the data.
4. **Query Capability**: Supports complex queries using SQL.
5. **Scalability**: Can handle large amounts of data and users.

#### 7. State four types of data type used to store data in tables?
1. **Integer**: Used for storing whole numbers.
2. **Varchar/String**: Used for storing variable-length text.
3. **Date/Time**: Used for storing dates and times.
4. **Boolean**: Used for storing true/false values.

#### 8. What is the purpose of a database management system (DBMS)?
The primary purpose of a DBMS is to provide a systematic way of creating, managing, and retrieving data. It allows users to interact with the data in an organized and controlled manner. A DBMS ensures data consistency, integrity, and security, while also providing support for data transactions, concurrent access, and efficient data management. 
