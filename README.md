# Library-Management-System
Library Management System

This is a SQL project that implements a library management system. The project provides a database schema and SQL queries to manage a library's collection of books, borrowers, and transactions.

Features
The Library Management System project offers various advanced features to efficiently manage a library's book collection. With this application, librarians can add, update, and delete books, library branches, and user data. Additionally, they can accurately track book loans, including managing copies available in each branch. This solution utilizes SQL queries to interact with the database and provides an intuitive interface for ease of use. Streamline library management and provide an optimal user experience with this management system.

Database Schema
The project includes the following tables in the database schema:
•	Book : Stores information about books in the library's collection, including book ID, title, Publisher name
•	Branch : Stores information about library branches, including branch ID, branch name, Address.
•	Borrower : Stores information about library borrowers, including borrower ID, name, address, contact details.
•	Loans : Stores information about book borrowing transactions, including loan ID, book ID, branch ID, borrower ID, loan date, due date, return date, and other attributes.
•	Copies : Stores information about book copies available in each branch, including copy ID, book ID, branch ID, number of copies, and other attributes.
•	Authors : Stores information about book authors, including book ID and author name.

Getting Started
To get started with the library management system project, follow these steps:
1.	Set up a SQL database system (e.g., MySQL, PostgreSQL).
2.	Create a new database.
3.	Execute the provided SQL queries to create the necessary tables and define the relationships between them.
4.	Use SQL queries to interact with the database and manage the library system.
