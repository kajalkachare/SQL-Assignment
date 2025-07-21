# Employee Database SQL Assignment.

This project contains SQL scripts designed for basic employee database management and operations. It includes table creation, data manipulation, and query execution to demonstrate SQL proficiency.

## 📄 File

- `Question With Answers.sql` – Main SQL script file with questions and their answers using SQL commands.

## 🗃️ Table Schema

The script creates a table named `employees` with the following columns:

- `employee_id` – Serial primary key
- `first_name` – First name of the employee
- `last_name` – Last name of the employee
- `department` / `dept_name` – Department name (later renamed)
- `salary` – Salary of the employee
- `joining_date` – Date of joining
- `age` – Age of the employee
- `email` – (Added later) Email of the employee

## 🧪 Operations Included

1. Retrieve employees' names and departments.
2. Increase salary by 10% for IT department employees.
3. Delete employees older than 34 years.
4. Add a new `email` column.
5. Rename the `department` column to `dept_name`.
6. Find employees who joined after Jan 1, 2021.
7. Change the data type of the `salary` column to `INTEGER`.
8. List all employees ordered by salary (descending).
9. Insert a new employee record.
10. Increment age by 1 for all employees.

## 💡 How to Use

1. Open your preferred SQL client (like PostgreSQL).
2. Run the script `Question With Answers.sql`.
3. Observe the effects of each SQL operation on the `employees` table.

## 📌 Requirements

- PostgreSQL or any SQL-compatible DBMS that supports standard SQL syntax.

---

Feel free to fork, modify, or use this script for learning and practice!
