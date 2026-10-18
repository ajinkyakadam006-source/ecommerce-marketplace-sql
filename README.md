# E-Commerce Marketplace Database

## Project Overview
An Oracle SQL database project designed to analyze
e-commerce marketplace operations, including customers,
products, orders, order items, and payments.

## Database Tables
1. CUSTOMERS
2. CATEGORIES
3. PRODUCTS
4. ORDERS
5. ORDER_ITEMS
6. PAYMENTS

## SQL Concepts Used
- Basic filtering and sorting
- Aggregate functions: COUNT, SUM, AVG, MIN, MAX
- INNER JOIN and LEFT JOIN
- Single-row and multiple-row subqueries
- GROUP BY and HAVING
- Business-oriented SQL analysis

## Project Files
- 01_create_tables.sql: Creates the six database tables.
- 02_insert_sample_data.sql: Inserts customers, categories,
  and products.
- 03_insert_orders_payments.sql: Inserts orders, order items,
  and payments.
- 04_business_queries.sql: Contains 50 SQL queries.

## Technologies
- Oracle Database 10g
- SQLPlus
- SQL

## How to Run
1. Connect to your Oracle database using SQLPlus.
2. Execute 01_create_tables.sql.
3. Execute 02_insert_sample_data.sql.
4. Execute 03_insert_orders_payments.sql.
5. Execute 04_business_queries.sql.

Run the scripts in order. Do not rerun insertion scripts
against an already populated database without resetting it.