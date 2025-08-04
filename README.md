# Elevate Labs - SQL Intern Task 1

## 📚 Task 1: Database Setup and Schema Design

### 🎯 Objective

To create a well-structured database schema by:
- Designing entities and their relationships
- Implementing the schema using SQL
- Generating an ER diagram

---

## 🛠️ Tools Used

- **MySQL Workbench**
- SQL

---

## 📚 Library Management System - Domain Content

### 📖 Introduction

The **Library Management System** is designed to efficiently manage and organize:
- Books
- Authors
- Library Members
- Borrowing activities

The system helps in:
- Tracking book inventory
- Managing author information
- Recording member registrations
- Monitoring book borrow and return records

---

### 🗂️ Identified Entities & Relationships

#### 📌 Entities:

1. **Author**
    - Stores information about book authors.
2. **Book**
    - Stores information about books in the library.
3. **Member**
    - Stores details of library members.
4. **Borrow**
    - Tracks which member has borrowed which book and when.

#### 🔗 Relationships:

- Each **Book** is written by one **Author**.
- Each **Member** can borrow multiple **Books**.
- Each **Borrow** record links a **Book** to a **Member**.

---

### ⚙️ Purpose of Each Table

| Table    | Purpose |
|----------|---------|
| Author   | Store author details like name and nationality. |
| Book     | Store book details including title, genre, and author. |
| Member   | Store member details like name, email, and joining date. |
| Borrow   | Record borrow transactions, mapping books to members with borrow and return dates. |

---

### ✅ SQL Script

- The full SQL script to create the database schema is uploaded 
