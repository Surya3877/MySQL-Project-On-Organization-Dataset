# MySQL-Project-on-Organization-Dataset

## Employee Database - SQL Query Practice
## Project Overview
This project focuses on writing and optimizing SQL queries to analyze an Employee Database. It includes 50+ SQL queries covering various scenarios such as retrieving employee details, salary analysis, department-wise statistics, and advanced query optimizations.

## Dataset Description
The database consists of three main tables:

## bonus.csv

WORKER_REF_ID: Worker ID reference

BONUS_AMOUNT: Bonus amount

BONUS_DATE: Date when the bonus was given

## title.csv

WORKER_REF_ID: Worker ID reference

WORKER_TITLE: Job title of the worker

AFFECTED_FROM: Date when the title became effective

## worker.csv

WORKER_ID: Unique Worker ID

FIRST_NAME: First name

LAST_NAME: Last name

SALARY: Salary

JOINING_DATE: Date when the worker joined

DEPARTMENT: Department

✅ Data Retrieval & Filtering:

Selected specific columns, filtered records using WHERE and HAVING clauses.

✅ Aggregation & Grouping:

Used GROUP BY and HAVING to summarize salary and employee distributions by department.

✅ Joins & Subqueries:

Combined multiple tables using INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL JOIN to extract meaningful insights.

Used subqueries to fetch the Nth highest salary and find employees earning the highest salary per department.

✅ Window Functions & Ranking:

Applied ROW_NUMBER(), RANK(), and DENSE_RANK() to rank employees based on salary.

✅ Performance Optimization:

Applied indexes and optimized queries for better performance.
