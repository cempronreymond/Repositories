# Programming Guide

## Programming Fundamentals

### 1. Variables and Data Types
- **Variables** are used to store data. They can be of various types such as integers, floats, strings, and booleans.
- **Example:**  
```python
name = "John"
age = 30
height = 5.9
is_student = True
```

### 2. Control Structures
- Control structures allow you to control the flow of execution based on certain conditions.
- **Example (If-Else in Python):**  
```python
if age < 18:
    print("Minor")
else:
    print("Adult")
```

### 3. Functions
- Functions allow you to encapsulate code for reuse.
- **Example:**  
```python
def greet(name):
    return f"Hello, {name}!"
```

## SQL Best Practices

### 1. Use Prepared Statements
- Prepared statements help prevent SQL injection attacks and improve performance.
- **Example:**  
```sql
PREPARE stmt FROM 'SELECT * FROM users WHERE id = ?';
SET @id = 1;
EXECUTE stmt USING @id;
```

### 2. Indexing
- Indexing speeds up the retrieval of rows from a database table.
- **Example:**  
```sql
CREATE INDEX idx_user_id ON users (user_id);
```

### 3. Normalization
- Normalize your database to reduce redundancy and improve data integrity.
  - **1NF:** Eliminate repeating groups.
  - **2NF:** Remove partial dependencies.
  - **3NF:** Remove transitive dependencies.

## Common Programming Languages

### 1. Python
- Python is great for beginners and has a huge library ecosystem.
- **Example:**  
```python
print("Hello, World!")
```

### 2. JavaScript
- JavaScript is essential for web development.
- **Example:**  
```javascript
console.log("Hello, World!");
```

### 3. Java
- Java is widely used in enterprise applications.
- **Example:**  
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

### 4. SQL
- SQL is the standard language for querying databases.
- **Example:**  
```sql
SELECT * FROM users;
```