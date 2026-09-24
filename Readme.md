# Online Bookstore SQL Analysis

## 📌 Project Overview

This project analyzes an **Online Bookstore database** using **PostgreSQL**. The database contains information about books, customers, and orders.

The project includes database creation, table relationships, data loading, and **20 SQL analysis questions** covering both basic and advanced SQL concepts.

## 🛠️ Tools & Technologies

* PostgreSQL
* SQL
* VS Code
* CSV datasets

## 📂 Project Structure

```text
Online-Bookstore-SQL-Analysis/
│
├── README.md
│
├── data/
│   ├── Books.csv
│   ├── Customers.csv
│   └── Orders.csv
│
└── sql/
    └── main.sql
```

## 🗄️ Database Schema

The project contains three tables:

### 1. Books

Contains information about the books available in the bookstore.

* Book_ID
* Title
* Author
* Genre
* Published_Year
* Price
* Stock

### 2. Customers

Contains customer information.

* Customer_ID
* Name
* Email
* Phone
* City
* Country

### 3. Orders

Contains information about customer orders.

* Order_ID
* Customer_ID
* Book_ID
* Order_Date
* Quantity
* Total_Amount

The `Orders` table is connected to both `Customers` and `Books` using foreign keys.

## 📊 SQL Analysis

### Basic Questions

The project answers questions such as:

1. Retrieve all books in the Fiction genre.
2. Find books published after 1950.
3. List customers from Canada.
4. Find orders placed in November 2023.
5. Calculate the total stock of books.
6. Find the most expensive book.
7. Find orders with a quantity greater than 1.
8. Find orders with a total amount greater than $20.
9. List all available book genres.
10. Find the book with the lowest stock.
11. Calculate total revenue generated from all orders.

### Advanced Questions

The project also covers:

1. Total books sold for each genre.
2. Average price of Fantasy books.
3. Customers who placed at least 2 orders.
4. Most frequently ordered book.
5. Top 3 most expensive Fantasy books.
6. Total quantity of books sold by each author.
7. Cities of customers who spent over $30.
8. Customer who spent the most.
9. Remaining stock after fulfilling orders.

## 🧠 SQL Concepts Used

* `SELECT`
* `WHERE`
* `DISTINCT`
* `ORDER BY`
* `LIMIT`
* Aggregate Functions

  * `SUM()`
  * `AVG()`
  * `COUNT()`
* `GROUP BY`
* `HAVING`
* `JOIN`
* `LEFT JOIN`
* `COALESCE()`
* `CASE`
* Date Filtering
* Foreign Keys
* Primary Keys
* Subqueries / Advanced SQL techniques
* PostgreSQL `SERIAL` and `NUMERIC` data types

## 🚀 How to Run

1. Install PostgreSQL.
2. Create the `OnlineBookstore` database.
3. Open `sql/main.sql` in PostgreSQL/pgAdmin.
4. Create the required tables.
5. Import the CSV files from the `data` folder.
6. Run the SQL queries to perform the analysis.


## 🎯 Project Objective

The main objective of this project is to practice SQL by working with a relational bookstore database and solving business-oriented data analysis questions.

This project demonstrates practical understanding of **data retrieval, aggregation, filtering, joins, grouping, and advanced SQL analysis using PostgreSQL**.
