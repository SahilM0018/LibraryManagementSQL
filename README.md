# Library Management System - SQL Project

Welcome to the **Library Management System**! 📚 This is a **MySQL-based** project designed to manage the complete lifecycle of library operations such as **book borrowing, member management, staff coordination, and fine handling**.

## 🚀 Project Overview

This project simulates a real-world library system, where books are managed, borrowed, and returned by library members. The system tracks:
- **Books**: Title, author, genre, available copies, etc.
- **Members**: Personal details of library members.
- **Staff**: Library staff roles and information.
- **Transactions**: Borrow and return activities.
- **Fines**: Late return fines calculation.

This project implements several features such as:
- **Database design** with multiple tables and relationships.
- **Stored procedures** for managing book borrowing and returning.
- **Views** for easy reporting (e.g., borrowed books, fines).
- **Analytics**: Get insights like most borrowed books, members with late returns, etc.

---

## 🛠 Project Features

- **Database Structure**: Efficient schema design with relationships between `books`, `members`, `staff`, `borrow_transactions`, and `fines`.
- **Stored Procedures**: Predefined procedures for borrowing books, handling fines, and more.
- **Dynamic Queries**: Real-time queries for reporting, tracking borrow history, and analyzing late returns.
- **Sample Data**: Populated with sample books, members, and transactions for quick testing and exploration.
- **Advanced SQL Features**: Use of views, triggers, and stored procedures for automation.

---

## ⚡ Features in Detail

### 1. **Book Management**
- Keep track of books with attributes like title, author, genre, and available copies.
- Easily check which books are available for borrowing.

### 2. **Member Management**
- Manage library members, their contact details, and borrowing activities.
- Track overdue items and apply fines.

### 3. **Staff Management**
- Keep records of library staff roles and responsibilities.
- Staff members can manage books, members, and transactions.

### 4. **Transactions (Borrowing & Returning)**
- Record when members borrow and return books.
- Automatically update the book’s availability based on borrow and return actions.

### 5. **Fines**
- Calculate late fees for books returned after the due date.
- Fine calculation based on number of late days and configurable fine rate.

### 6. **Reports & Analytics**
- View current borrow status and overdue books.
- Track the most borrowed books and identify frequent late-returning members.

---

## 📦 Files in this Repository

### 1. `01_create_database_and_tables.sql`
This file contains the SQL statements to create the database (`library_db`) and all necessary tables, including:
- **books**
- **members**
- **staff**
- **borrow_transactions**
- **fines**

### 2. `02_insert_sample_data.sql`
Populates the database with example data for easy testing and exploration of the system.

### 3. `03_views_and_procedures.sql`
This file includes SQL scripts 

## ⚙️ Tools & Technologies
- **Database:** MySQL 
- **Language:** SQL  
- **Concepts Used:**  
  - Database Normalization  
  - Foreign Key Relationships  
  - Subqueries & Joins  
  - Triggers and Views  


