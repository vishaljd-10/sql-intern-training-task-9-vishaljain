
📌 Overview

This project focuses on understanding and implementing SQL subqueries using real-world employee and department data. The task demonstrates how subqueries work in different SQL clauses, how they compare with JOIN-based solutions, and how to debug common subquery-related errors. All queries are executed using MySQL / MariaDB (XAMPP – phpMyAdmin).
---------------------------------------------------------------------------------------------------------
🎯 Objectives

Understand nested, correlated, and aggregate-based subqueries

Use subqueries inside WHERE, FROM, and SELECT clauses

Perform department-wise salary analysis

Compare subqueries vs JOINs for the same business logic

Analyze execution flow of nested queries

Identify scenarios where subqueries are unavoidable

Practice debugging common SQL subquery errors
---------------------------------------------------------------------------------------------------------

🗂 Database Structure

🔹 Employees Table

emp_id (Primary Key)

emp_name

dept_id

salary

🔹 Departments Table

dept_id (Primary Key)

dept_name

Employees are linked to departments using a foreign key relationship to ensure data integrity.
---------------------------------------------------------------------------------------------------------


🧪 Tasks Performed
1️⃣ Added Department & Salary Data

Extended the existing employees table using ALTER TABLE

Populated salary and department mapping data

2️⃣ Subqueries with Aggregate Functions

Identified employees earning more than the average salary

Found highest-paid employees using subqueries

3️⃣ Subqueries in Different Clauses

WHERE clause for filtering based on aggregates

FROM clause using derived tables

SELECT clause for calculated values per row

4️⃣ Subqueries vs JOINs

Implemented the same logic using both approaches

Compared readability and performance implications

5️⃣ Correlated Subqueries

Performed department-wise salary comparisons

Observed row-by-row execution behavior

6️⃣ Execution Flow Analysis

Studied how inner queries execute before outer queries

Understood correlated vs non-correlated execution

7️⃣ Practical Use Cases

Identified situations where JOINs are insufficient

Used EXISTS and aggregate-based subqueries

8️⃣ Debugging Common Errors

Fixed “subquery returns more than one row” issues

Resolved alias and scope-related errors

---------------------------------------------------------------------------------------------------------

🛠 Tools & Technologies

MySQL / MariaDB

XAMPP

phpMyAdmin

SQL (DDL & DML)

---------------------------------------------------------------------------------------------------------

📌 Conclusion

This task strengthened my understanding of SQL subqueries by applying them to real employee and department data. It provided hands-on experience with advanced querying techniques, execution flow analysis, and performance-aware query design.
