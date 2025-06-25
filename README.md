# Task-2

# Student Record Management System (Java CLI Project)

##  Overview

This project is a **Command-Line Interface (CLI)** based Java application that implements a basic **Student Record Management System**. It simulates how records (like those in a real-world database) can be stored and managed using Java’s built-in features like **classes**, **collections**, and **standard input/output**.

This system helps understand the core concepts of **Object-Oriented Programming (OOP)** and **data structure handling** (like `ArrayList`) through a practical example of managing students' information.

---

## Objective

- To create a CRUD system (**Create, Read, Update, Delete**) for managing student records.
- To practice working with user-defined classes, data structures, and CLI-based applications.
- To reinforce concepts of encapsulation, object manipulation, and interactive programming.

---



## 🧰 ools & Technologies

- Language: Java
- IDE: VS Code
- CLI Interface: Terminal

---

##  System Workflow (Theoretical)

### 1. Program Start
- The main method continuously displays a menu using a `do-while` loop.
- It prompts the user to choose an action (1 to 5).

### 2. Data Structure
- Student records are stored in a **Java `ArrayList<Student>`**.
- Each student is represented as an object with:
  - `id` (Integer)
  - `name` (String)
  - `marks` (Double)

### 3. Menu Options

#### ➕ Add Student
- User enters the ID, name, and marks.
- A new `Student` object is created and added to the list.

#### 📃 View Students
- Iterates over the ArrayList.
- Prints each student's data using the `toString()` method.

#### ✏️ Update Student
- Asks for the student ID.
- Searches the list; if found, asks for new name and marks.
- Updates the corresponding student object.

#### ❌ Delete Student
- Asks for the student ID.
- Searches and removes the student from the list if found.

#### 🚪 Exit
- Program terminates the loop and ends execution.

---

##  File Structure

The project contains the following two main files, both written in Java:

1. Student.java
This file defines the Student class, which models each student's data. It includes:

Fields: id, name, and marks

A constructor to initialize a student object

Getter and setter methods to access and modify fields (following encapsulation)

A toString() method to return a readable string representation of a student



2. StudentManagementSystem.java
This is the main file that runs the program. It performs the following functions:

Maintains a list of students using ArrayList<Student>

Uses Scanner to read input from the user

Displays a menu with options inside a loop

Calls respective methods to:

Add a student to the list

View all student records

Update student details by ID

Delete a student by ID

Exit the program
