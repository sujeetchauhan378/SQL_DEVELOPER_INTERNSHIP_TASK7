# SQL_DEVELOPER_INTERNSHIP_TASK7

# Task 7 – Creating Views

## 🎯 Objective
Learn to create, use, and manage SQL views for abstraction, security, and reusable SQL logic.

## 🛠 Tools Used
- DB Browser for SQLite
- MySQL Workbench

---

## 📌 Overview
A **view** is a virtual table in SQL that displays data from one or more tables using a predefined query.  

**Why use views?**
- Simplify complex queries
- Restrict access to sensitive data
- Provide reusable SQL logic

---

## 📂 Steps & Examples

### 1️⃣ Create a Sample Table
```sql
CREATE TABLE Employees (
    emp_id INT PRIMARY KEY,
    emp_name VARCHAR(50),
    department VARCHAR(50),
    salary DECIMAL(10, 2)
);

INSERT INTO Employees VALUES
(1, 'Alice', 'IT', 60000),
(2, 'Bob', 'HR', 45000),
(3, 'Charlie', 'Finance', 70000),
(4, 'David', 'IT', 65000);
