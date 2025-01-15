
Tags: [[Databases]]

2025-01-15:09:24

# Big ideas
- Row=Entity=Record
- Column=Field=Attribute
- Table=Entity Set



* **NULL** is a special value in a database that represents the absence of a value in a table column. it doesn't mean zero or space or empty , it's used when the value is unknown yet.
* **Primary Key**: A unique identifier for each record in a table. It ensures that no two rows have the same value in the primary key column(s) and that the value is not null.
    
    _Example_: `id` column in a `users` table.
    
- **Foreign Key**: A column (or set of columns) in one table that *refers *to the primary key in another table. It establishes a relationship between the two tables.
    
    _Example_: `user_id` column in an `orders` table referencing the `id` column in the `users` table.
* Primary key can't be null or empty and it should be one column as a good practice and should be an integer

  ## **Referential Integrity** 
  it ensures that relationships between tables in a database remain consistent. It enforces rules to maintain valid references in a relational database.

### Key Points:

1. **Valid Foreign Keys**: A foreign key in one table must match an existing primary key value in the referenced table or be null.  
    _Example_: An `order` must reference an existing `user_id` in the `users` table.
    
2. **Cascading Actions**: Changes in the parent table (e.g., delete or update a primary key) can trigger actions (e.g., cascade delete or update) to maintain consistency.
    
3. **Prevents Orphan Records**: Ensures that no child record (with a foreign key) exists without a corresponding parent record.
   
   ![[Pasted image 20250115110732.png]]

**Redundancy** refers to duplicated data in a database, such as storing the same information multiple times or storing data derivable from other data. While it can be useful in some cases, redundancy often causes issues like increased storage usage and difficulty maintaining consistency. Updating one copy of redundant data can lead to inconsistencies if other copies are not updated. To minimize redundancy, normalization techniques can be applied to organize data and reduce duplication.

**Normalization** is the process of organizing database data to reduce redundancy and improve integrity. It involves breaking data into smaller, atomic pieces and linking them through relationships. This minimizes duplication and simplifies database management. Enforcing constraints like unique and foreign keys helps prevent redundant data. Further details on normalization will be covered later.

**Data Integrity** ensures the accuracy, consistency, and reliability of data throughout its lifecycle. It guarantees that data is complete, accurate, and trustworthy. Factors like human error, hardware/software failures, security breaches, and transfer errors can impact integrity. Maintaining data integrity involves implementing policies, procedures, and technologies such as encryption, backups, and access controls.

### Types of Data integrity
- **Entity Integrity**: Ensures each record in a table is unique and identifiable, typically using primary keys.
- **Referential Integrity**: Maintains relationships between tables and prevents orphaned records, typically using foreign keys.
- **Domain Integrity**: Ensures data values fall within acceptable ranges, such as valid dates in date fields or numbers in numeric fields.
- **Business Integrity**: Ensures data adheres to specific business rules and requirements, such as account balance limits or confidentiality rules.

Maintaining data integrity is **critical** for organizations that rely on accurate and trustworthy data to make informed decisions. Without data integrity, organizations risk making decisions based on incomplete, inaccurate, or unreliable data, which can lead to poor outcomes, financial losses, and damage to reputation.
* To maintain data integrity we use Constraints.

# Constraints 
In the context of databases, **constraints** are rules or conditions applied to the data to ensure its integrity and consistency. Constraints can be applied to individual columns or entire tables and are used to enforce various rules and restrictions on the data. By using constraints, you can help ensure that your data is: 
- Accurate 
- Consistent 
- Easy to manage
# Common Types of Database Constraints

1. **Primary Key Constraint**: Ensures that each row in a table is unique by requiring one or more columns to have unique values. Prevents duplicate rows.

2. **Foreign Key Constraint**: Links two tables by ensuring that a value in one table matches a value in another. Helps maintain consistent relationships between tables.

3. **Unique Constraint**: Ensures that the values in a column (or group of columns) are unique across all rows in the table, preventing duplicates.

4. **Not Null Constraint**: Ensures that a column cannot have empty (null) values, making sure the data is complete and accurate.

5. **Check Constraint**: Ensures that the data in a column meets specific conditions, preventing invalid or unwanted data from being added.

What is the difference between Primary Key Constraint and Unique Constraint?
Primary Key is Unique but it does not allow NULL  while Unique allows NULL. So primary key columns have Unique Constraint + Not Null Constraint by default.

# What Can You Do With SQL?

- **Execute Queries**: Run queries against a database to fetch and manipulate data.  
- **Retrieve Data**: Extract data from a database.  
- **Insert Records**: Add new records to a database.  
- **Update Records**: Modify existing records in a database.  
- **Delete Records**: Remove records from a database.  
- **Create Databases**: Set up new databases.  
- **Create Tables**: Define new tables within a database.  
- **Create Stored Procedures**: Write reusable SQL code blocks for specific tasks.  
- **Create Views**: Create virtual tables based on database queries.  
- **Set Permissions**: Control access to tables, procedures, and views.

# Types of SQL Statements

1. **Data Definition Language (DDL)**  
   Used to define and manage database structures, such as creating or modifying tables and schemas.

2. **Data Manipulation Language (DML)**  
   Used to manipulate data in a database, including inserting, updating, and deleting records.

3. **Data Control Language (DCL)**  
   Used to control access to the database, such as granting or revoking permissions.

4. **Transaction Control Language (TCL)**  
   Used to manage transactions in a database, such as committing or rolling back changes.

5. **Data Query Language (DQL)**  
   Used to query and retrieve data from a database, typically using the `SELECT` statement.



