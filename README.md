# 👨‍💼 Employee Management System using Python & MySQL

This project is an Employee Management System that performs operations such as adding, removing, promoting, and displaying employee records. It uses Python and MySQL to manage employee data via a command-line interface.

---

## 📌 Problem Statement

The goal is to build an employee database management tool where the user can:

- Add new employee records
- Delete existing employee records
- Promote employees by updating their salaries
- View all employee data in the system

---

## 🗃️ Dataset (Database)

The project uses a MySQL database named `emp` with a single table `employees`. The table has the following columns:

- `id` – Employee ID (Primary Key)
- `name` – Employee Name
- `post` – Designation/Post
- `salary` – Employee Salary

You can set up the table using the provided `emp_schema.sql`.

---

## 🔧 Technologies Used

- Python
- MySQL
- MySQL Connector for Python
- Jupyter Notebook

---

## ⚙️ Operations Performed

1. **Add Employee** – Insert new employee details.
2. **Remove Employee** – Delete an employee using their ID.
3. **Promote Employee** – Update an employee's salary.
4. **Display Employees** – View all records in the database.

---

## 📝 SQL Schema

```sql
CREATE DATABASE IF NOT EXISTS emp;

USE emp;

CREATE TABLE IF NOT EXISTS employees (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    post VARCHAR(100),
    salary FLOAT
);
