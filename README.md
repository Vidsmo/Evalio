# Evalio
Project Description
Evalio is a Java-based crash-resistant examination management system designed to conduct secure and reliable examinations. The system allows teachers to create exams, students to attempt them, and automatically evaluates MCQ-based responses.

The key feature of Evalio is its auto-save and crash recovery mechanism, which ensures that student progress is not lost due to unexpected system failures or shutdowns. The system can detect incomplete exam sessions and restore them from the last saved state.

🎯 Key Features
Role-based access (Admin / Teacher / Student)

Exam creation and question management

MCQ-based automatic evaluation

Countdown timer for exams

Auto-save mechanism

Crash detection and session recovery

Secure data handling

Terminal-based implementation (Phase 1 & 2)

🏗️ System Architecture
Evalio follows a layered architecture:

User Interaction Layer

Terminal-based interface

Login and menu handling

Application Logic Layer

Authentication

Exam management

Timer control

Evaluation logic

Backup & Recovery Layer

Auto-save mechanism

File handling

Session restoration

Database Layer (Phase 3)

Persistent storage using MySQL/SQLite

JDBC integration

🛠️ Technologies Used
Programming Language: Java

Concepts Used:

Object-Oriented Programming

Collections Framework

Exception Handling

Multithreading

File Handling

IDE: IntelliJ IDEA / Eclipse / NetBeans

Database (Phase 3): MySQL / SQLite

🚀 Project Phases
✅ Phase 1 – Core System (Terminal Based)
Login system

Role-based menu

Exam creation

Student exam attempt

MCQ evaluation

Timer implementation

✅ Phase 2 – Crash Recovery
Auto-save using file handling

Session tracking

Resume exam functionality

Exception handling improvements

✅ Phase 3 – Database Integration
JDBC connectivity

Secure data storage

Performance optimization

Final testing and documentation

🔄 Workflow
User logs in (Teacher / Student)

Teacher creates exam

Student starts exam

System auto-saves progress

If crash occurs, system detects incomplete session

Student resumes from last saved point

Exam is evaluated and results are generated

🎯 Project Objective
The objective of Evalio is to build a reliable and fault-tolerant examination system that ensures zero data loss, maintains fairness in evaluation, and demonstrates real-world application of core Java concepts.

📈 Future Enhancements
Cloud-based backup

Encrypted data storage

Analytics dashboard

GUI-based interface

AI-based cheating detection

📌 Conclusion
Evalio is a practical and scalable Java application that ensures crash-resistant exam conduction and seamless recovery. By integrating multithreading, file handling, collections, and structured design, the system demonstrates a strong foundation in real-world software development principles.

