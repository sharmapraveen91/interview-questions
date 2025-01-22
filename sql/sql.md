# SQL Interview Questions

## 1. **SQL Query Fundamentals**

1. **What is the difference between `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, and `FULL OUTER JOIN`? Can you provide examples of when to use each type of join?**
2. **Explain the concept of `GROUP BY` and `HAVING`. How does `HAVING` differ from `WHERE`?**
3. **What is a `CROSS JOIN`? How does it work, and in what scenarios would you use it?**
4. **Can you explain the difference between `UNION` and `UNION ALL`? When would you prefer to use one over the other?**
5. **How would you optimize a query that contains multiple `JOIN` operations? What are some techniques to improve performance?**

---

## 2. **Subqueries and Nested Queries**

1. **What is a correlated subquery, and how does it differ from a non-correlated subquery? Provide an example.**
2. **Explain the difference between a subquery in the `SELECT` clause and a subquery in the `WHERE` clause. Which scenarios would require each?**
3. **How do you optimize subqueries that return large datasets? Are there any alternatives to using subqueries in these cases?**
4. **Can a `JOIN` be used in place of a subquery? Explain the scenarios where replacing a subquery with a `JOIN` might improve query performance.**
5. **How would you use the `EXISTS` clause in a query? Provide an example where `EXISTS` is more efficient than `IN`.**

---

## 3. **Indexes and Performance Optimization**

1. **What are indexes in SQL, and how do they improve query performance? What are the different types of indexes (e.g., B-tree, Hash)?**
2. **How do you decide whether to create an index on a column or a set of columns? What factors affect index creation in a large database?**
3. **What is a composite index, and how does it differ from a single-column index? When is it appropriate to use composite indexes?**
4. **What is a covering index, and how does it improve performance?**
5. **What is index fragmentation? How can you identify and fix index fragmentation to improve database performance?**

---

## 4. **Normalization and Database Design**

1. **Explain the different normal forms (1NF, 2NF, 3NF, BCNF). What are the rules for each, and why is normalization important in database design?**
2. **What is denormalization, and in what scenarios might you choose to denormalize a database schema for performance reasons?**
3. **How would you design a relational database schema for a complex application, like an e-commerce system? What factors would you consider in your schema design?**
4. **What are the benefits and drawbacks of using foreign keys in relational databases? When should they be used, and when should they be avoided?**
5. **What are some potential issues with database design when scaling a system horizontally (e.g., partitioning, sharding)?**

---

## 5. **Transactions and Concurrency Control**

1. **What is a database transaction? Explain the ACID properties of a transaction. Why are they important in relational databases?**
2. **What is the difference between `COMMIT` and `ROLLBACK`? When would you use each in a transaction?**
3. **Explain the different isolation levels in SQL (e.g., `READ COMMITTED`, `REPEATABLE READ`, `SERIALIZABLE`). How do they impact concurrency and locking?**
4. **What is a deadlock, and how would you resolve it in a database system?**
5. **What is optimistic vs. pessimistic locking? When should each technique be used to prevent concurrency issues?**

---

## 6. **Window Functions and Analytical Queries**

1. **What is a window function in SQL? How do `ROW_NUMBER()`, `RANK()`, and `DENSE_RANK()` differ, and when would you use each?**
2. **How would you write a query to calculate a moving average over a specified window in SQL?**
3. **Explain the use of `PARTITION BY` and `ORDER BY` in window functions. How do they affect the result set?**
4. **Can you explain the difference between `LEAD()` and `LAG()` window functions? How would you use them to compare values across rows?**
5. **What is the purpose of `NTILE()` in SQL? How is it different from other ranking functions like `RANK()` or `ROW_NUMBER()`?**

---

## 7. **Joins and Complex Join Operations**

1. **Explain the difference between `INNER JOIN`, `LEFT JOIN`, and `OUTER JOIN` in terms of performance.**
2. **How would you write a query that returns rows where a value in one table doesn't exist in another table (anti-join)?**
3. **What is a self-join, and when would you use it? Provide an example where a self-join is useful.**
4. **Explain the concept of a `FULL OUTER JOIN`. How is it different from `LEFT JOIN` and `RIGHT JOIN`?**
5. **How do you handle `JOIN` operations with `NULL` values in SQL?**

---

## 8. **Advanced Query Techniques**

1. **What is the `WITH` clause (Common Table Expression - CTE)? How does it improve query readability and maintainability?**
2. **How would you write a recursive query using `WITH` in SQL? Provide an example for querying hierarchical data (e.g., organizational chart, category tree).**
3. **What is the difference between `GROUP_CONCAT()` (or `STRING_AGG()`) and `GROUP BY`? Provide an example of when each would be useful.**
4. **Explain the use of `DISTINCT` in SQL. How does it work, and what are the potential performance implications of using it in large datasets?**
5. **How would you query the second-highest salary from an employees table, or the nth highest salary? Provide a solution using window functions or subqueries.**

---

## 9. **SQL Functions and Expressions**

1. **Explain the difference between `TRIM()`, `LTRIM()`, and `RTRIM()` functions in SQL. How are they used in data cleaning?**
2. **What is the purpose of `COALESCE()` and `NULLIF()`? How do these functions help handle `NULL` values in queries?**
3. **What is the difference between `CAST()` and `CONVERT()` in SQL? When would you use one over the other?**
4. **What is a regular expression (REGEXP) in SQL, and how can you use it to perform complex string matching or extraction?**
5. **How would you implement data type conversion in SQL? Provide examples of using `CAST` or `CONVERT` to change data types in queries.**

---

## 10. **Data Integrity and Constraints**

1. **What is referential integrity in SQL, and how do foreign keys enforce it?**
2. **Explain the difference between `PRIMARY KEY`, `UNIQUE`, and `INDEX` in terms of database constraints.**
3. **How do you handle `NULL` values in a column with a `NOT NULL` constraint?**
4. **What are `CHECK` constraints, and how do you use them to enforce data integrity in SQL?**
5. **What are `UNIQUE` constraints, and how are they different from primary keys? Can a table have multiple `UNIQUE` constraints?**

---

## 11. **SQL Optimization and Query Tuning**

1. **What are the most common performance bottlenecks in SQL queries, and how would you identify them using tools like `EXPLAIN` or `EXPLAIN ANALYZE`?**
2. **What are the advantages and disadvantages of using `JOIN` vs. `IN` or `EXISTS` for filtering results? Which is more efficient?**
3. **How can you improve the performance of a query involving `GROUP BY` and `HAVING` clauses?**
4. **What is the role of `query execution plans` in SQL optimization, and how do you interpret them?**
5. **Explain the concept of `query caching`. How does it work, and how can you enable or disable query caching for a particular query in SQL?**

---

## 12. **Advanced SQL Concepts**

1. **What are `materialized views` in SQL? How do they differ from regular views, and when would you use them?**
2. **What is a `trigger` in SQL? How would you create a trigger to enforce business rules or automatically update other tables?**
3. **What are `stored procedures` and `functions` in SQL? How do they differ, and when would you use one over the other?**
4. **How do you implement versioning for data changes (e.g., audit tables) in SQL? What techniques do you use to track changes in records?**
5. **Explain the concept of database partitioning and sharding. How do they help with scaling large datasets, and what are the challenges involved?**

---

