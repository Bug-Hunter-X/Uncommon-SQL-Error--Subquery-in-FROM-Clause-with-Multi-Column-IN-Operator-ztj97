# Uncommon SQL Error: Subquery in FROM Clause with Multi-Column IN Operator

This repository demonstrates a common SQL error involving the use of subqueries in the FROM clause and the `IN` operator with multiple columns returned from the subquery.  Many SQL dialects do not support subqueries directly in the FROM clause, and the use of `IN` with multiple columns often requires adjustments. 

The `bug.sql` file contains the erroneous SQL code.  The `bugSolution.sql` file demonstrates a corrected approach, showing multiple ways to achieve the intended result.