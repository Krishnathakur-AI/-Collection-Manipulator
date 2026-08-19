Student Data Organizer

A simple Python-based Student Data Organizer that demonstrates the use of Python collections, functions, loops, conditional statements, user input, and basic CRUD operations.

 Project Overview

This project provides a menu-driven console application for managing student records. Student information is stored using a list of dictionaries, while subjects are maintained as a list inside each student record.

The notebook contains the implementation of a Student Data Organizer with options to add, display, update, delete students, and display their subjects.

 Features

 Add a new student

 Display all student records

 Update existing student information

 Delete a student by Student ID

 Display subjects for a specific student

 Exit the application

 Handles invalid menu choices and missing student IDs

 Student Information

Each student record contains:

Student ID

Name

Age

Grade

Date of Birth

Subjects

The data is organized in the following structure:

students = [
    {
        "id": "101",
        "name": "Student Name",
        "age": 18,
        "grade": "12",
        "dob": "2008-01-01",
        "subjects": ["Python", "Math", "Science"]
    }
]

🛠️ Technologies Used

Python 3

Jupyter Notebook

Python Lists

Python Dictionaries

Functions

Loops

Conditional Statements

User Input

List Comprehension

String Manipulation

 Menu Options

When the program starts, it displays the following menu:

=========================================
      STUDENT DATA ORGANIZER
=========================================

1. Add Student
2. Display All Students
3. Update Student
4. Delete Student
5. Display Subjects Offered
6. Exit

=========================================

1. Add Student

Takes student details from the user and stores them as a dictionary inside the students list.

2. Display All Students

Displays all currently stored student records in a readable format.

3. Update Student

Searches for a student using their Student ID and allows the user to update:

Name

Age

Grade

Date of Birth

Subjects

Leaving a field blank keeps its existing value.

4. Delete Student

Removes a student record from the students list using the Student ID.

5. Display Subjects Offered

Displays the subjects associated with a particular student.

6. Exit

Terminates the application.

 How to Run

Using Jupyter Notebook

Open the .ipynb file in Jupyter Notebook, JupyterLab, or Google Colab.

Run the code cell.

Use the displayed menu in the input prompts.

Select an option by entering its corresponding number.

Using Python

The notebook can also be converted to a Python script and executed with Python 3.

python filename.py

 Concepts Demonstrated

This project is useful for practicing:

Lists — storing multiple student records

Dictionaries — representing individual student details

Nested collections — storing subjects inside student dictionaries

Functions — separating application features into reusable functions

Loops — iterating through student records and keeping the menu running

Conditional logic — handling menu selections and search results

List comprehension — cleaning and formatting subject input

CRUD operations — Create, Read, Update, and Delete student records

 Project Structure

.
├── PR. 3 Collection Manipulator (1).ipynb
└── README.md

 Future Improvements

Possible improvements include:

Add input validation for age and Student ID

Prevent duplicate Student IDs

Store records permanently using JSON or a database

Add student search functionality

Add sorting and filtering options

Improve the user interface

Add exception handling for invalid inputs
