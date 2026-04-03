# SQL-project-
📚 Online Bookstore SQL Project

This project is a complete SQL-based database system designed for managing an Online Bookstore. It includes database creation, table structure, data import, and a wide range of queries for data analysis.

🚀 Features
Database Setup
Creates a database named OnlineBookstore
Defines three main tables:
Books
Customers
Orders
Relational Design
Establishes relationships using foreign keys:
Orders linked to Customers
Orders linked to Books
Data Import
Supports CSV data import for:
Books
Customers
Orders
📊 Queries Included
🔹 Basic Queries
Filter books by genre (e.g., Fiction)
Find books published after a certain year
Retrieve customers by country
View orders within a specific date range
Calculate total stock and revenue
Identify most expensive and lowest-stock books
🔹 Intermediate Queries
Orders with quantity > 1
Orders exceeding a specific amount
Distinct genres available
🔹 Advanced Queries
Total books sold per genre
Average price by genre
Customers with multiple orders
Most frequently ordered book
Top expensive books by genre
Total sales per author
High-spending customer locations
Customer who spent the most
Remaining stock after fulfilling orders
🛠️ Technologies Used
SQL (PostgreSQL syntax)
CSV data handling
📁 File Structure
sql project querry.sql – Main SQL script containing:
Database setup
Table creation
Data import commands
Analytical queries
💡 Use Case

This project is ideal for:

Beginners learning SQL
Practicing database design and joins
Understanding real-world e-commerce data analysis

If you want, I can also:

Make it shorter (for repo description line)
Add badges (GitHub style)
Or convert it into a polished README.md with formatting and icons 👍
yes 

Here’s a polished GitHub README.md with badges, clean formatting, and visuals you can directly paste into your repo:

📚 Online Bookstore SQL Project








A complete SQL database project that simulates an Online Bookstore system.
It demonstrates database design, data import, and powerful querying for business insights.

🚀 Overview

This project builds a relational database called OnlineBookstore and performs various operations such as:

Creating structured tables
Importing CSV data
Running analytical queries
Generating business insights
🗂️ Database Schema
📘 Books
Book_ID (Primary Key)
Title, Author, Genre
Published Year
Price, Stock
👤 Customers
Customer_ID (Primary Key)
Name, Email, Phone
City, Country
🛒 Orders
Order_ID (Primary Key)
Customer_ID (Foreign Key)
Book_ID (Foreign Key)
Order Date
Quantity, Total Amount
🔗 Relationships
A customer can place multiple orders
A book can appear in multiple orders
Orders act as a bridge between Customers and Books
📥 Data Import

The project supports importing data from CSV files:

Books.csv
Customers.csv
Orders.csv

Using SQL commands like:

COPY books FROM 'path/to/file.csv' WITH CSV HEADER;
📊 Queries Included
🔹 Basic Queries
Filter books by genre (e.g., Fiction)
Books published after 1950
Customers from a specific country
Orders within a date range
Total stock calculation
Most expensive book
🔹 Intermediate Queries
Orders with quantity > 1
Orders above a certain value
Unique genres list
🔹 Advanced Queries
📈 Total books sold per genre
💰 Revenue calculation
🧑 Customers with multiple orders
📚 Most frequently ordered book
🏆 Top 3 expensive Fantasy books
✍️ Total books sold per author
🌍 Cities with high-spending customers
👑 Highest spending customer
📦 Remaining stock after orders
🛠️ Tech Stack
SQL (PostgreSQL)
CSV Data Handling
Relational Database Design
💡 Learning Outcomes

This project helps you understand:

Database normalization
Joins and aggregations
Real-world query scenarios
Business data analysis using SQL
📁 Project File
sql project querry.sql

Contains:

Database creation
Table definitions
Data import commands
All queries (basic → advanced)
🎯 Use Cases

✔ SQL practice for beginners
✔ Academic mini-project
✔ Portfolio project for data roles
✔ Interview preparation

⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
