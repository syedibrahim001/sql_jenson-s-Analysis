# sql_jenson-s-Analysis
Jensen's Data Analysis Project

Project Overview:
This project focuses on deriving insights into customer behavior, staff performance, inventory management, and store operations at Jensen's, a retail chain, using an SQL dataset. By leveraging various SQL techniques such as Windows Functions, subqueries, Common Table Expressions (CTEs), joins, and EXISTS, we explore critical aspects of the business. The insights gained help optimize inventory, improve staff performance, and enhance customer experience.

Key Questions Answered:
The analysis involves crafting complex SQL queries to answer the following business questions:

1. The total number of products sold by each store, along with the store name.
2. The cumulative sum of quantities sold for each product over time.
3. The product with the highest total sales (quantity * price) for each category.
4. The customer who spent the most money on orders.
5. The highest-priced product for each category.
6. The total number of orders placed by each customer per store.
7. The names of staff members who have not made any sales.
8. The top 3 most sold products in terms of quantity.
9. The median value of the price list.
10. A list of all products that have never been ordered (using EXISTS).
11. The names of staff members who have made more sales than the average number of sales by all staff members.
12. Customers who have ordered at least one product from every category.

Key SQL Techniques Used:
This project employs several advanced SQL techniques, each enhancing the analysis of the business's operational data:

Windows Functions: These functions, such as RANK(), DENSE_RANK(), and SUM() OVER(), were applied to calculate cumulative sums of quantities sold, rank products based on sales, and calculate performance metrics like the total sales per product and customer ranking. These functions allowed for more detailed analysis of trends and customer/product performance.

Subqueries: Subqueries were utilized for various calculations and filtering operations. For example, one subquery identified the customer who spent the most money on orders by aggregating total expenditure per customer. These subqueries enable modular analysis within larger queries.

Common Table Expressions (CTEs): CTEs were used to organize complex queries by breaking them down into more manageable parts. CTEs helped to calculate total sales for each product category, which could then be referenced in the main query to determine the product with the highest total sales.

Joins: To combine related data from multiple tables, joins (INNER, LEFT, RIGHT) were used. These joins linked the sales table with the product and customer tables to calculate revenue and orders placed by each customer, allowing us to perform deep analysis across different data points such as customer orders, staff sales, and store operations.

EXISTS: The EXISTS operator was leveraged to identify products that had never been ordered. This approach helped efficiently check the existence of related records (i.e., sales data) and filter products accordingly.

Tools and Technologies Used:
SQL: For querying and deriving insights from the dataset.

Database: A relational database system (e.g., MySQL, PostgreSQL) was used to store and query the dataset.

Windows Functions: For advanced analytics, such as ranking and cumulative sums.


Conclusion:
This project demonstrates how SQL can be applied to real-world business problems. By utilizing advanced SQL techniques such as joins, windows functions, CTEs, subqueries, and EXISTS, this analysis provides valuable insights into customer behavior, staff performance, inventory management, and store operations. These insights can inform strategic decision-making at Jensen's and lead to better business outcomes.
