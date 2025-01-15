
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