# Main_Flow_Technologies
# Task 1 – Student Management System (SQL Developer Internship)

> Completed as part of the SQL Developer Internship at **Main Flow Services and Technologies Pvt. Ltd.**

This project involves designing and implementing a **Student Management System** using **MySQL**. It aims to provide a functional database solution for managing student details and analyzing academic performance through SQL queries.

---

## Objective

Develop a robust SQL-based system to:

- Store student personal and academic data
- Track and analyze student performance across multiple subjects
- Identify top performers based on total scores
- Perform comparative analysis of performance by gender and grades

---

## Database Design & Table Structure

### Database: `StudentManagement`

### Table: `Students`

| Column Name    | Data Type         | Description                           |
|----------------|-------------------|-------------------------------------|
| StudentID      | INT (Primary Key) | Auto-incremented unique identifier  |
| Name           | VARCHAR(50)       | Full name of the student             |
| Gender         | VARCHAR(1)        | 'M' for Male, 'F' for Female         |
| Age            | INT               | Age of the student                   |
| Grade          | VARCHAR(10)       | Academic grade (e.g., A, B, C)       |
| MathScore      | INT               | Marks scored in Mathematics          |
| ScienceScore   | INT               | Marks scored in Science               |
| EnglishScore   | INT               | Marks scored in English               |

---

## Functionalities & SQL Queries

- Insert and manage student records with detailed academic scores
- Retrieve complete student details
- Calculate average scores in Math, Science, and English using aggregate functions
- Identify highest scoring student(s) based on total marks
- Analyze student distribution by grade
- Compare average subject scores across genders
- Filter students scoring above certain thresholds (e.g., above 80 in Math)
- Update student information dynamically based on their unique `StudentID`

---

## Included Files

| File Name             | Description                                     |
|-----------------------|-------------------------------------------------|
| `create_database.sql` | Script to create database and `Students` table |
| `insert_data.sql`     | SQL statements to insert sample student records |
| `queries.sql`         | Collection of SQL queries for data retrieval and updates |

---

## 📸 Visual References

- **Table Structure**  
- **Sample Data Inserted**  
- **Queries Output (Average Scores, Top Scorers, etc.)**

---

## 🧠 Skills Developed

- Designing and implementing relational databases  
- Writing complex SQL queries involving `JOIN`, `GROUP BY`, `WHERE`, and aggregate functions like `AVG` and `SUM`  
- Data analysis and reporting using SQL  
- Data insertion, updating, and management  

