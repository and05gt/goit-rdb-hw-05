# Nested queries. Code reuse

## Homework Assignment Description

1. Write an SQL query that displays the `order_details` table and the `customer_id` field from the `orders` table, one for each row in the `order_details` table.\
   This should be done using a nested query within the `SELECT` statement.

2. Write an SQL query that will display the `order_details` table. Filter the results so that the corresponding record from the `orders` table satisfies the condition `shipper_id=3`.\
   This should be done using a subquery in the `WHERE` clause.

3. Write an SQL query nested within the `FROM` clause that selects rows from the `order_details` table where `quantity > 10`. For the resulting data, find the average value of the `quantity` field — group by `order_id`.

4. Solve Exercise 3 using the `WITH` clause to create a temporary table named `temp`. If you are using a version of MySQL earlier than 8.0, create this query in a manner similar to the one shown in the lecture notes.

5. Create a function with two parameters that divides the first parameter by the second. Both parameters and the return value must be of type `FLOAT`.\
   Use the `DROP FUNCTION IF EXISTS` construct. Apply the function to the `quantity` attribute of the `order_details` table. The second parameter can be any number of your choice.
