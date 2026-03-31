# Campus Course & Records Manager (CCRM)

A simple Java console application for managing students, courses, and enrollments.

---

## Student Details

**Name:** Siddharth Ranjan
**Registration Number:** 24BAI10125

---

## Project Description

This project is a console-based system developed using Java to manage basic academic records. It allows users to interact with student, course, and enrollment data through a menu-driven interface.

The aim of this project is to demonstrate how core programming concepts can be applied in a structured way. The focus is on clarity, modular design, and practical implementation rather than complexity.

---

## Key Features

* View and manage student records
* Maintain course details
* Enroll students into courses
* Display enrollment information
* Read and write data using CSV files
* Simple command-line interaction

---

## Technologies and Concepts Used

The project demonstrates the following concepts:

* Object-Oriented Programming (OOP)
* Enums for fixed values
* Builder pattern for object creation
* Singleton pattern for configuration
* File handling using Java NIO
* Basic recursion utilities
* CLI-based interaction

---

## Project Structure

```id="g6m4n9"
src/
  edu/ccrm/
    domain/      -> Core data classes
    service/     -> Business logic
    io/          -> File operations
    util/        -> Helper methods
    config/      -> Application settings
    cli/         -> CLI handling

data/
  students.csv
  courses.csv
  enrollments.csv
```

---

## Requirements

* Java JDK (8 or above)
* Command line / terminal

---

## How to Run the Project

### Step 1: Navigate to the project folder

```id="q1r9fd"
cd path/to/project
```

---

### Step 2: Compile the project

```id="f3s8zx"
javac -d out $(find src -name "*.java")
```

---

### Step 3: Run the application

```id="h5k2jm"
java -cp out edu.ccrm.Main
```

---

### For Windows (PowerShell)

```powershell id="p9z7wa"
Get-ChildItem -Recurse -Filter *.java | % { $_.FullName } > sources.txt
javac -d out @sources.txt
java -cp out edu.ccrm.Main
```

---

## Data Files

The `data` folder contains CSV files used by the application:

* `students.csv` → student records
* `courses.csv` → course details
* `enrollments.csv` → enrollment information

These files are used to simulate real-world data storage and retrieval.

---

## Notes

* The project follows a modular structure using Java packages.
* Data is handled using CSV files for simplicity.
* The application is intended for learning purposes and demonstration of concepts.

---

## Final Thoughts

This project helped in understanding how multiple programming concepts can be combined to build a structured application. It also provided practical experience in organizing code and handling data in a simple system.

---
