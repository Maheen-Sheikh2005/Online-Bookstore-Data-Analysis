Online Bookstore Data Analysis (SQL Portfolio Project)
Project Overview
This project focuses on analyzing an online bookstore's database using PostgreSQL. The goal is to solve real-world business problems by answering 20 analytical questions. These questions are divided into basic and advanced levels, covering inventory management, customer behavior, and sales performance.

Database Structure
The project uses three tables that connect with each other:

books: Contains details about books (ID, title, author, genre, price, and current stock).

customers: Contains customer profiles (ID, name, email, city, and country).

orders: Tracks transactions (Order ID, Customer ID, Book ID, order date, quantity, and total amount).

Core Skills Demonstrated
Data Filtering: Using WHERE, BETWEEN, IN, and LIKE to find specific records.

Aggregations: Using COUNT(), SUM(), AVG(), and arithmetic expressions to calculate business metrics.

Data Grouping: Using GROUP BY and filtering grouped data using the HAVING clause.

Table Joins: Connecting multiple tables using INNER JOIN and LEFT JOIN to combine customer, order, and book data.

Null Handling: Using COALESCE() to replace empty data with zero for accurate math calculations.

Key Business Questions Answered
Basic Level
Filtering books by specific genres (e.g., "Fiction") and publication years.

Tracking customer locations and specific high-value orders.

Identifying low-stock books (less than 10 units) for inventory alerts.

Advanced Level
Calculating total revenue and monthly sales trends.

Finding total books sold and average prices grouped by each author and genre.

Identifying top-spending customers and tracking remaining stock after fulfilling all customer orders.

How to Run This Project
Run the database setup script to create the tables and import the CSV data.

Run the basic and advanced SQL query files in any SQL editor (like pgAdmin) to see the results.


