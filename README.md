## Zen Class DB model - MySQL Day 2 Task
## Overview
 Note:  `This repository contains a word document if you want to see you can download it`.
- This repository contains the MySQL database schema and SQL statements for designing a Zen class model. The model includes tables for storing information about students, mentor, classes, class, and enrollment details.
- I used a primary key and foreign key to connect with.

## Database Schema
The database schema consists of the following tables:

`student`: Stores information about Zen class students, including their student ID, name.
`mentor`: Contains details of Zen class teachers, such as their mentor ID, name, specialization.
`class`: Represents the Zen classes offered, including class ID, title, description, duration, and teacher ID.
`task`: Stores the schedule details for each Zen class, including schedule ID, class ID, day, time, and location.
`coordinator`: Tracks the enrollment of students in Zen classes, with enrollment ID, student ID, class ID, and enrollment date.
## Getting Started
- To set up the Zen class model in your MySQL environment, follow these steps:

- Ensure you have MySQL installed on your machine. You can download and install MySQL from the official MySQL website.
- Create a new database for the Zen class model using the MySQL command-line interface or a MySQL client such as MySQL Workbench.
- Import the provided SQL file containing the database schema and table definitions into your MySQL database.
- Once the tables are created, you can populate them with sample data using SQL INSERT statements.

