# Study_Tracker_App
The study tracker app is a console-based java application designed to help students systematically log, track, summarize, and export their study activities.

## Project Overview

The **Study Tracker Application** is a Java-based console application that helps students track and manage their daily study activities. Users can record study sessions, view logs, generate summaries, and export study data to a CSV file for future analysis.

This project demonstrates the implementation of Object-Oriented Programming (OOP), Java Collections Framework, File Handling, and Data Management concepts.

---

## Features 

* Add new study logs
* View all study records
* Generate study summary by date
* Generate study summary by subject
* Export study logs to CSV format
* Menu-driven console interface
* Dynamic storage using ArrayList
* Simple and user-friendly design

---

## Technology Used 

* **Programming Language:** Java
* **Core Java Concepts:** OOP, Collections, Exception Handling
* **Data Structures:** ArrayList, TreeMap
* **File Handling:** CSV Export
* **Date API:** LocalDate

---

## Project Structure 

```text
StudyTrackerApp.java
│
├── StudyLog
│   ├── Date
│   ├── Subject
│   ├── Duration
│   └── Description
│
├── StudyTracker
│   ├── InsertLog()
│   ├── DisplayLog()
│   ├── ExportCSV()
│   ├── SummaryByDate()
│   └── SummaryBySubject()
│
└── StudyTrackerApp
    └── Main Menu Driven Application
```

---

## Functionalities 

### 1. Add Study Log

Allows users to record a study session with:

* Subject Name
* Study Duration (Hours)
* Description

### 2. View Study Logs

Displays all recorded study sessions in a structured format.

### 3. Export Study Logs

Exports all study records into a CSV file named:

```text
StudyTracker.csv
```

### 4. Summary By Date

Calculates and displays total study hours for each date.

### 5. Summary By Subject

Calculates and displays total study hours for each subject.

---

## How To Run Project 

### Step 1: Compile the Program

```bash
javac StudyTrackerApp.java
```

### Step 2: Run the Program

```bash
java StudyTrackerApp
```

---

## Sample Menu 

```text
------------------------------------------------------
---------Welcome to Study Tracker Application---------
------------------------------------------------------

1 : Insert new study log
2 : View all study log
3 : Export study log to CSV file
4 : Summary of Study log by date
5 : Summary of Study log by subject
6 : Exit the application
```

---

## Sample Output 

### Adding a Study Log

```text
Please enter the name of subject
Java

Enter the time period of your study in hours
2.5

Please provide the description of your study
Studied OOP Concepts

Study log gets stored successfully
```

### Viewing Study Logs

```text
---------Log report of Study Tracker Application----------

2026-06-18 | Java | 2.5 | Studied OOP Concepts
2026-06-18 | Python | 1.5 | File Handling

----------------------------------------------------------
```

### Exporting to CSV

```text
Data gets exported in CSV : StudyTracker.csv
```

### Summary By Date

```text
Date : 2026-06-18
Total Study Duration : 4.0 Hours
```

### Summary By Subject

```text
Subject : Java
Total Study Duration : 2.5 Hours

Subject : Python
Total Study Duration : 1.5 Hours
```

---

## CSV Export Format 📄

```csv
Date,Subject,Duration,Description
2026-06-18,Java,2.5,Studied OOP Concepts
2026-06-18,Python,1.5,File Handling
```

---

## Concepts Used 

* Object-Oriented Programming (OOP)
* Classes and Objects
* Encapsulation
* Constructors
* ArrayList
* TreeMap
* File Handling
* Exception Handling
* LocalDate API
* Menu-Driven Programming

---

## Learning Outcomes 

* Understanding real-world application design in Java
* Working with Java Collections Framework
* Implementing file handling operations
* Managing and processing user-generated data
* Generating summaries using TreeMap
* Applying OOP concepts effectively
* Building interactive console applications

---

## Future Enhancements 

* User Authentication System
* Database Integration (MySQL)
* Search Study Logs
* Edit/Delete Study Logs
* Weekly and Monthly Reports
* Data Import from CSV
* PDF Report Generation
* GUI using Java Swing or JavaFX
* Analytics Dashboard with Charts

---

## Author 

**Nitya Rajesh More**

Third Year Information Technology Student

---

⭐ If you found this project useful, consider giving it a star on GitHub!
