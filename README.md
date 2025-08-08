
## Basic SQL SELECT Queries – Employee Database
# Overview
This project demonstrates basic SQL SELECT queries using an example Employee Database.
It covers retrieving data, filtering rows, sorting, limiting output, pattern matching, and using aliases.

# Database & Table Structure
Database: EMPLOYEE_DB
Table: EMPLOYEES

# Columns:

- EMPLOYEE_ID: INT (Primary Key) – Unique employee ID

- FIRST_NAME: VARCHAR(255) – Employee's first name

- LAST_NAME: VARCHAR(255) – Employee's last name

- DEPARTMENT: VARCHAR(255) – Department name

- SALARY: DECIMAL(10,2) – Monthly salary

- HIRE_DATE: DATE – Date of joining

# Sample Data
1, SRAVANI, BODAPATI, HR, 50000.00, 2024-05-06
2, NIRAJA, KAMANA, MARKETING, 30000.00, 2023-02-02
3, MANISHA, SHAK, AUDIT, 40000.00, 2025-01-19
4, LAVANYA, PONDARU, FINANCE, 25000.00, 2022-04-29
5, MANOJ, PITANI, IT, 20000.00, 2020-10-07
6, GANESH, ANUKULA, AUDIT, 15000.00, 2022-12-26

# Queries Demonstrated
- Retrieve all data from the table

- Retrieve specific columns such as first name, last name, and department

- Filter rows using WHERE clause

- Apply AND condition to combine multiple filters

- Apply OR condition to match any of multiple conditions

- Search by patterns using LIKE

 -Retrieve rows in a range using BETWEEN

- Sort results in ascending or descending order

- Limit the output to a specific number of rows

- Remove duplicate values for a column using DISTINCT

- Use aliases to rename column headings
