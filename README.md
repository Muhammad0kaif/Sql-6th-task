# SQL Subqueries

# ✅ 1. Scalar and Correlated Subqueries

* **Scalar Subquery** returns a single value.
  Example: Selecting customers whose age is greater than the average age.

* **Correlated Subquery** runs once for each row in the outer query.
  Example: Finding customers who have placed more than one order.



# ✅ 2. Subqueries with IN, EXISTS, =

* **IN** is used to filter values that exist in a list returned by a subquery.
  Example: Customers who have placed at least one order.

* **EXISTS** checks for the existence of related records.
  Example: Displaying customers who have any matching orders.

* **=** compares a single value from the outer query with the result of a subquery.
  Example: Getting the name of the customer who placed a specific order.
