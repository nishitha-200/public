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

 ER DIAGRAM

WhatsApp Image 2026-09-04 at 12 18 33 PM (1)

# Online Course Management System
Project Description

The Online Course Management System is a database management project designed to manage students, courses, trainers, enrollments, payments, and certificates.

The system stores and organizes information about students and their course enrollments. It also maintains course details, trainer information, payment records, and certificates in a structured relational database.

Objectives

To maintain student information efficiently.
To manage course details.
To manage trainer information.
To manage student course enrollments.
To maintain payment information.
To manage certificates issued to students.
To establish relationships between different entities using a relational database.
Technologies Used

MySQL
SQL
GitHub
Main Entities

The Online Course Management System contains the following entities:

Student
Course
Trainer
Enrollment
Payment
Certificate
Entity Description

Student

Stores student personal and contact information.

Attributes:

Student_ID (Primary Key)
Name
Email
Phone
Address
Course

Stores information about the courses offered in the system.

Attributes:

Course_ID (Primary Key)
Course_Name
Description
Duration
Fee
Trainer_ID (Foreign Key)
Trainer

Stores information about trainers who conduct courses.

Attributes:

Trainer_ID (Primary Key)
Name
Email
Phone
Specialization
Enrollment

Stores information about students enrolled in courses.

Attributes:

Enrollment_ID (Primary Key)
Student_ID (Foreign Key)
Course_ID (Foreign Key)
Enrollment_Date
Status
Payment

Stores payment details related to course enrollments.

Attributes:

Payment_ID (Primary Key)
Enrollment_ID (Foreign Key)
Amount
Payment_Date
Payment_Method
Payment_Status
Certificate

Stores certificate information issued to students for courses.

Attributes:

Certificate_ID (Primary Key)
Student_ID (Foreign Key)
Course_ID (Foreign Key)
Issue_Date
Certificate_Number
Relationships

One student can have many enrollments.
One course can have many enrollments.
One trainer can conduct many courses.
One enrollment can have multiple payment records.
One student can have multiple certificates.
One course can have multiple certificates.
ER Diagram

The Entity Relationship Diagram represents the entities, attributes, primary keys, foreign keys, and relationships of the Online Course Management System.

![Online course management system];

Key Features

Student information management
Course information management
Trainer information management
Student enrollment management
Payment record management
Certificate management
Primary key and foreign key relationships
Structured relational database design
Database Design

The system follows relational database concepts. Primary keys are used to uniquely identify records, while foreign keys are used to establish relationships between related tables.

Project Outcome

This project demonstrates the design and management of an Online Course Management System using SQL and MySQL. It provides a structured way to manage students, courses, trainers, enrollments, payments, and certificates.

Repository

The project is maintained using GitHub for version control, project files, and documentation.