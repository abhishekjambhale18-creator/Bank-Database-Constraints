# 🏦 SQL Lab 2 – Bank Database Constraints

![SQL](https://img.shields.io/badge/SQL-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Intermediate-blue?style=for-the-badge)

> Adding Primary Key, Foreign Key, Unique, Not Null, and Check constraints to the Bank Database for better data integrity.

---

### 📌 Project Overview
This lab continues from the basic Bank Database setup.  
It focuses on applying important **SQL constraints** to ensure data accuracy, uniqueness, and proper relationships between tables.

---

### ✨ Constraints Applied

| Constraint Type | Table     | Details                                     |
|-----------------|-----------|---------------------------------------------|
| `CHECK`         | Accounts  | Balance must be ≥ 1000                      |
| `PRIMARY KEY`   | Customers | CustomerId set as Primary Key               |
| `NOT NULL`      | Customers | FirstName cannot be empty                   |
| `UNIQUE`        | Customers | Email must be unique                        |
| `FOREIGN KEY`   | Accounts  | CustomerId references Customers(CustomerId) |

---

### 🛠️ Operations Performed
- Added `CHECK` constraint on Accounts (Minimum Balance)
- Dropped unused table `AccountBranches`
- Added Primary Key on `Customers`
- Made `FirstName` NOT NULL
- Added Unique constraint on `Email`
- Added `CustomerId` column in Accounts
- Created Foreign Key relationship between Accounts and Customers

---

### 🛠️ Skills Demonstrated
- `ALTER TABLE`
- `PRIMARY KEY`
- `FOREIGN KEY`
- `UNIQUE`
- `NOT NULL`
- `CHECK` constraint
- Table relationships

---

### 🚀 How to Run
1. Make sure Lab 1 (Bank Database Setup) is already executed
2. Open MySQL Workbench
3. Run the `BankDatabase2.sql` script

---

### 🧰 Tools Used
MySQL

---
**Series Navigation**  
← [Lab 1 – Bank Database Setup](https://github.com/abhishekjambhale18-creator/Bank-Database-SQL) | [Lab 3 – Bank Database Relationships](https://github.com/abhishekjambhale18-creator/Bank-Database-Relationships) →
