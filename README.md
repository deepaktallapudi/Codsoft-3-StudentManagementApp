# Codsoft-3-StudentManagementApp# Student Management System

A Java program that manages student records, allowing users to add, remove, search, update, and display student information.

## Introduction

"Student Management System" is a Java program that provides basic functionalities to manage student records. It allows users to perform operations like adding a new student, removing a student, searching for a student by roll number, updating student information, and displaying all student records.

## Features

- Add a new student with their name, roll number, and grade.
- Remove a student from the records using their roll number.
- Search for a student by their roll number and view their information.
- Update the name and grade of a student using their roll number.
- Display all student records.

## How to Use

1. Clone or download this repository to your local machine.

2. Open a terminal (command prompt) and navigate to the project directory.

3. Compile the Java source code:
   ```
   javac StudentManagementApp.java
   ```

4. Run the program:
   ```
   java StudentManagementApp
   ```

5. Follow the on-screen instructions to interact with the Student Management System.

## Example

Suppose you use the following sequence of actions in the program:
```
Student's Management System Menu
1. Add Student
2. Remove Student
3. Search for Student
4. Display All Students
5. Update Student Information
6. Exit

Enter your choice: 1
Enter Name: John Doe
Enter Roll Number: 123
Enter Grade: A
Student added successfully!

Student's Management System Menu
1. Add Student
2. Remove Student
3. Search for Student
4. Display All Students
5. Update Student Information
6. Exit

Enter your choice: 3
Enter Roll Number of the student to search: 123
Student found: Name: John Doe, Roll Number: 123, Grade: A

Student's Management System Menu
1. Add Student
2. Remove Student
3. Search for Student
4. Display All Students
5. Update Student Information
6. Exit

Enter your choice: 5
Enter Roll Number of the student to update: 123
Current Student Information: Name: John Doe, Roll Number: 123, Grade: A
Enter new Name (leave blank to keep the current name): John Smith
Enter new Grade (leave blank to keep the current grade): B
Student information updated successfully!

Student's Management System Menu
1. Add Student
2. Remove Student
3. Search for Student
4. Display All Students
5. Update Student Information
6. Exit

Enter your choice: 4
Name: John Smith, Roll Number: 123, Grade: B

Student's Management System Menu
1. Add Student
2. Remove Student
3. Search for Student
4. Display All Students
5. Update Student Information
6. Exit

Enter your choice: 2
Enter Roll Number of the student to remove: 123
Student removed successfully!

Student's Management System Menu
1. Add Student
2. Remove Student
3. Search for Student
4. Display All Students
5. Update Student Information
6. Exit

Enter your choice: 4
(No students to display)

Student's Management System Menu
1. Add Student
2. Remove Student
3. Search for Student
4. Display All Students
5. Update Student Information
6. Exit

Enter your choice: 6
Exiting the application.
```

## How it Works

The program utilizes a `Student` class to represent individual students with attributes like name, roll number, and grade. The `StudentManager` class is responsible for managing student records, providing methods to add, remove, search, update, and display students. The `StudentManagementApp` class serves as the user interface, allowing users to interact with the system through a simple text-based menu.

## Screenshots


![Screenshot 2023-07-25 155614](https://github.com/deepaktallapudi/Codsoft-3-StudentManagementApp/assets/103422044/5410b6d7-c53c-4cfc-9e6a-ab66dbc30286)

![Screenshot 2023-07-25 155638](https://github.com/deepaktallapudi/Codsoft-3-StudentManagementApp/assets/103422044/123b4e71-1076-40c7-8eee-225e71f2ead5)
