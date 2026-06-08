# SQL Practice

This folder contains SQL exercises completed using PostgreSQL and pgAdmin 4.

## Tools Used

- PostgreSQL 18
- pgAdmin 4

## Topics Covered

### 1. Database Setup
Created a database called:

```sql
CREATE DATABASE qa_practice;
```

### 2. Create Table

Created a table named `users`:

```sql
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    email VARCHAR(100)
);
```

### 3. Insert Data

Added sample records to the table:

```sql
INSERT INTO users (first_name, last_name, email)
VALUES
('Anna', 'Kowalska', 'anna@test.com'),
('Jan', 'Nowak', 'jan@test.com'),
('Maria', 'Wisniewska', 'maria@test.com');
```

### 4. Select Data

Retrieved all records from the table:

```sql
SELECT * FROM users;
```

### 5. Filtering Data

Used WHERE clause:

```sql
SELECT * FROM users
WHERE first_name = 'Anna';
```

Used LIKE operator:

```sql
SELECT * FROM users
WHERE first_name LIKE 'M%';
```

### 6. Sorting Data

Sorted records alphabetically:

```sql
SELECT * FROM users
ORDER BY last_name ASC;
```

### 7. Update Data

Updated existing records:

```sql
UPDATE users
SET last_name = 'Nowicka'
WHERE first_name = 'Anna';
```

### 8. Delete Data

Deleted a record:

```sql
DELETE FROM users
WHERE first_name = 'Jan';
```

### 9. Count Records

Counted users in the table:

```sql
SELECT COUNT(*) AS total_users
FROM users;
```

### 10. Select Specific Columns

Retrieved only selected columns:

```sql
SELECT first_name, email
FROM users;
```

## Screenshots

Screenshots of executed queries and results are stored in the `Screenshots` folder.


- SQL_001_Create_Table.png
- SQL_002_Insert_Users.png
- SQL_003_Select_All.png
- SQL_004_Update_User.png
- SQL_005_Like_Query.png
- SQL_006_Count_Users.png
- SQL_007_Select_Columns.png
- SQL_008_Insert_Multiple_Records.png
- SQL_009_Delete_User.png
- SQL_010_Verification.png
- SQL_011_Where_Filter.png
- SQL_012_Order_By.png
  
## Skills Demonstrated

- Database creation
- Table creation
- Data insertion
- Data retrieval
- Filtering records
- Sorting results
- Updating records
- Deleting records
- Aggregate functions
- Working with PostgreSQL
- Using pgAdmin 4
