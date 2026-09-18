# Library Management System

A Library Management System developed using Java.

## Student Details

Name: Krishna Singh
Register Number: 24BCY10114
Course: Programming in Java

## Project Overview

The Library Management System is a command-line Java application designed to manage books and library members.

The system allows users to add and remove books, search for books, register members, issue books, return books, and display information through a terminal-based menu.

## Features

- Add new books
- Remove books
- Display all books
- Search books by title or author
- Register library members
- Display registered members
- Issue books to members
- Return books
- Maximum of 3 books per member
- Duplicate ID validation
- Input validation
- Exception handling
- File-based data storage
- Command-line interface

## Technologies Used

- Java
- Java Collections Framework
- Object-Oriented Programming
- File Handling
- Exception Handling

## Project Structure

library-management-system/
├── src/
│   ├── Main.java
│   ├── Book.java
│   ├── Member.java
│   ├── Library.java
│   └── FileManager.java
├── data/
│   ├── books.txt
│   └── members.txt
└── README.md

## Requirements

Java Development Kit (JDK) 17 or later.

Check Java installation using:

java -version

javac -version

## Setup and Execution

1. Clone the repository:

git clone https://github.com/Kroos008/library-management-system.git

2. Open the project directory:

cd library-management-system

3. Compile the project:

javac -d out src/*.java

4. Run the project:

java -cp out Main

## Main Menu

1. Add Book
2. Remove Book
3. Display Books
4. Search Book
5. Register Member
6. Display Members
7. Issue Book
8. Return Book
9. Exit

## Data Storage

Book and member information is stored in the data folder using text files.

## Future Enhancements

- Due dates and fine calculation
- Book categories
- Administrator login
- Sorting and filtering
- Database integration

## Author

Krishna Singh
Register Number: 24BCY10114
