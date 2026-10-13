# Student Management Database (MySQL)

A simple database-driven application built with MySQL.

## Setup
1. Install MySQL Server
2. Create the database: CREATE DATABASE student_db;
3. Import the data: mysql -u root -p student_db < student_db.sql

## Contents
- students table (id, name, email, course, created_at)
- add_student stored procedure
- UNIQUE constraint on email, NOT NULL on name