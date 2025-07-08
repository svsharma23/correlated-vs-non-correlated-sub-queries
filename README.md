
# SQL Subqueries Comparison: Correlated vs Non-Correlated

This project demonstrates how the same SQL problems can be solved using both correlated and non-correlated subqueries. These examples were solved using **PostgreSQL** and focus on understanding subquery logic through practical customer-order scenarios.

## 🔍 Key Concepts

- **Correlated Subquery**: Refers to a subquery that uses values from the outer query. It runs once for each row selected by the outer query.
- **Non-Correlated Subquery**: Independent of the outer query. It runs only once and its result is used by the outer query.

Questions are : 
-- 1	List customers who placed more than one delivered order
-- 2	List customers who never placed any order
-- 3	List customers who have only placed cancelled orders
-- 4	List customers who have placed at least one high-value order (e.g. amount > ₹1000)
-- 5	List customers whose total spend is above average spend of all customers
