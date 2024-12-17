# Incorrect Use of AVG() in WHERE Clause
This example demonstrates a common error in SQL queries involving the use of aggregate functions like AVG() within the WHERE clause.  The query attempts to compare individual salaries to the average salary but fails because aggregate functions work on the entire result set, not row-by-row.

The solution involves using a subquery to pre-calculate the average salary and then filter based on that value.
