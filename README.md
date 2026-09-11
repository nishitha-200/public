# public
Online Course Management System
A MySQL-based Online Course Management System developed as a team project.

📌 Project Description

The Online Course Management System is a database management project designed to manage students, trainers, courses, enrollments, payments, and certificates.

The system uses MySQL to store and manage data and demonstrates important SQL concepts such as primary keys, foreign keys, unique constraints, check constraints, joins, subqueries, views, and stored procedures.

🎯 Objectives

Manage student information
Manage trainer information
Manage course details
Manage student enrollments
Track course payments
Manage certificates
Maintain relationships between different entities
Practice SQL queries and database concepts
🛠️ Technologies Used

MySQL
SQL
GitHub
🗂️ Database Tables

The project contains the following tables:

Student – Stores student details
Trainer – Stores trainer details
Course – Stores course information
Enrollment – Stores student course enrollments
Payment – Stores payment details
Certificate – Stores certificate information
🔗 Relationships

One Trainer can handle multiple Courses.
One Student can enroll in multiple Courses.
One Course can have multiple Students through Enrollment.
Enrollment is connected with Payments.
Students and Courses are connected with Certificates.
🔐 Constraints Used

The project demonstrates:

Primary Key
Foreign Key
NOT NULL
UNIQUE
CHECK
DEFAULT
💻 SQL Concepts Used

CREATE DATABASE
CREATE TABLE
INSERT
UPDATE
DELETE
SELECT
WHERE
JOIN
Aggregate Functions
Subqueries
Views
Stored Procedures
Constraints
📊 Sample Operations

The project includes queries to:

Display students and their enrolled courses
Display courses with trainer details
Display enrollment and payment details
Find courses with fees above the average course fee
Display student course details using a view
Retrieve a student's courses using a stored procedure
▶️ How to Run

Install MySQL / MySQL Workbench.
Open the SQL file: online_management_system_project.sql
Select the database.
Execute the required SQL statements.
Use the verification queries to view the tables and data.
📁 Project Files

online_management_system_project.sql – Complete database schema, sample data, and SQL queries
README.md – Project documentation
👨‍💻 Project Type

Team Project

📄 License

This project is created for educational and learning purposes.