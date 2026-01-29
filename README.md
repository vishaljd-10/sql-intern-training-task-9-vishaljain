# Task 9: Writing Subqueries (Nested Queries)

## Objective
Learn how to write and analyze nested SQL queries (subqueries) and understand their execution flow.

---

## Tools Used
- MySQL Workbench  
- Alternatives: PostgreSQL, BigQuery Sandbox

---

## Table Used
### employees
| Column Name | Data Type |
|------------|----------|
| emp_id | INT (Primary Key) |
| emp_name | VARCHAR |
| department | VARCHAR |
| salary | INT |

---

## Key Concepts Covered

### 1. Subquery in WHERE Clause
Used to filter records based on aggregated values.

Example:
```sql
SELECT emp_name
FROM employees
WHERE salary > (SELECT AVG(salary) FROM employees);
