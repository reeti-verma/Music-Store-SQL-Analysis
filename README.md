# Music Store SQL Analysis

## Project Overview

This project focuses on analyzing a Music Store database using PostgreSQL and SQL. The analysis answers business questions related to customers, invoices, employees, artists, tracks, and genres.

## Objectives

* Analyze customer purchasing behavior
* Identify top customers and cities by sales
* Analyze invoices and sales
* Find popular genres and artists
* Practice SQL joins, aggregations, subqueries, CTEs, and window functions

## Dataset

The project uses a Music Store relational database containing information about employees, customers, invoices, tracks, albums, artists, and genres.

**Dataset:** [music_store_database.sql](./music_store_database.sql)

## SQL Queries

The project contains 10 SQL queries that answer different business questions related to the Music Store database.

**Solved Queries:** [Query_solved.sql](./Query_solved.sql)

## Business Questions

1. Who is the senior-most employee based on job title?
2. Which countries have the most invoices?
3. What are the top three invoice values?
4. Which city has the highest sum of invoice totals?
5. Who is the best customer based on total spending?
6. Which customers listen to Rock music?
7. Which are the top 10 Rock artists by number of tracks?
8. Which tracks are longer than the average song length?
9. How much do customers spend on the best-selling artist?
10. What is the most popular genre in each country?

## SQL Concepts Used

* SELECT
* WHERE
* DISTINCT
* GROUP BY
* ORDER BY
* LIMIT
* JOIN
* COUNT()
* SUM()
* AVG()
* Subqueries
* Common Table Expressions (CTEs)
* Window Functions
* ROW_NUMBER()
* Aggregate Functions

## Database Tables

* Employee
* Customer
* Invoice
* Invoice Line
* Track
* Album
* Artist
* Genre

## Tools Used

* PostgreSQL
* SQL
* pgAdmin

## Project Structure

```text
Music-Store-SQL-Analysis/
│
├── music_store_database.sql
├── Query_solved.sql
└── README.md
```

## Key Learning

Through this project, I practiced writing SQL queries to analyze a relational database and learned how to use joins, aggregate functions, subqueries, CTEs, and window functions to solve business questions.

## Conclusion

This project helped me strengthen my SQL skills and understand how SQL can be used to analyze business data and generate meaningful insights from a relational database.
