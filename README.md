# Library Management System

This repository contains the database schema and sample queries for a simple Library Management System.

**Features:**

* **Tracks book information:** Includes ISBN, title, category, rental price, availability status, author, and publisher.
* **Manages employees:** Stores employee details like ID, name, position, salary, and assigned branch.
* **Handles customers:** Keeps track of customer IDs, names, addresses, and registration dates.
* **Maintains book issuance and return:** Includes tables for tracking issued books, return dates, and associated customers.
* **Provides basic querying capabilities:** 
    * Retrieves available books.
    * Lists employees by salary.
    * Finds books issued by specific customers.
    * Counts books in each category.
    * Selects employees with high salaries.
    * Identifies customers who haven't issued any books.
    * Counts employees in each branch.
    * Finds customers who issued books in a specific month.
    * Retrieves book titles from issuance history.
    * Counts employees in branches with more than 5 employees.
    * Displays branch managers and their addresses.
    * Finds customers who issued books with high rental prices.

**Database Structure:**

* **Tables:**
    * `Branch`
    * `Employee`
    * `Books`
    * `Customer`
    * `IssueStatus`
    * `ReturnStatus`

**How to Use:**

1. **Create the database:** Execute the SQL scripts in the `sql/` directory to create the database and tables.
2. **Insert data:** Populate the tables with own data using SQL `INSERT` statements.
3. **Run queries:** Execute the provided SQL queries to retrieve the desired information.


