📌 Complaint Management System (Java + JDBC)
📖 Project Description

The Complaint Management System is a Java-based console application developed using JDBC and MySQL.
It allows users to register, view, update, and manage complaints efficiently.

This project demonstrates the implementation of:

Java OOP concepts

DAO Design Pattern

JDBC Connectivity

MySQL Database Integration

Layered Architecture (DTO, DAO, Service)

🛠️ Technologies Used

☕ Java (JDK 8 or above)

🗄️ MySQL

🔌 JDBC

🧩 DAO Design Pattern

🖥️ Console-based Application

📂 Project Structure
ComplaintManagementSystem/
│
├── ComplaintDTO.java
├── ComplaintDAO.java
├── ComplaintDAOImpl.java
├── ComplaintService.java
├── DBConnection.java
├── MainApp.java
├── DatabaseComplaint.sql
└── README.md
🏗️ Architecture Overview
1️⃣ DTO Layer

ComplaintDTO.java

Stores complaint data.

Acts as a data carrier between layers.

2️⃣ DAO Layer

ComplaintDAO.java – Interface defining database operations.

ComplaintDAOImpl.java – Implements database operations using JDBC.

3️⃣ Service Layer

ComplaintService.java

Contains business logic.

4️⃣ Utility Layer

DBConnection.java

Manages database connectivity.

5️⃣ Main Class

MainApp.java

Entry point of the application.

⚙️ Features

➕ Add New Complaint

📋 View All Complaints

🔍 Search Complaint by ID

✏️ Update Complaint Status

❌ Delete Complaint

🔐 Database Connectivity using JDBC

🗄️ Database Setup

Install MySQL.

Open MySQL Workbench or Command Line.

Run the SQL file:

DatabaseComplaint.sql

Update database credentials in:

DBConnection.java

Modify:

private static final String URL = "jdbc:mysql://localhost:3306/your_database";
private static final String USER = "root";
private static final String PASSWORD = "your_password";
▶️ How to Run the Project
Step 1:

Clone the repository

git clone https://github.com/your-username/your-repo-name.git
Step 2:

Open in IDE (Eclipse / IntelliJ / VS Code)

Step 3:

Add MySQL JDBC Driver (Connector J)

If using Maven:

<dependency>
    <groupId>mysql</groupId>
    <artifactId>mysql-connector-java</artifactId>
    <version>8.0.33</version>
</dependency>

Or manually add MySQL Connector JAR file.

Step 4:

Run MainApp.java

📸 Sample Console Output
1. Add Complaint
2. View Complaints
3. Search Complaint
4. Update Complaint
5. Delete Complaint
6. Exit

Enter your choice:
🎯 Learning Objectives

Understand DAO Pattern

Perform CRUD operations using JDBC

Manage database connections

Apply layered architecture in Java

Implement exception handling

🚀 Future Improvements

Add GUI (JavaFX / Swing)

Add Admin & User roles

Implement Authentication

Convert to Web Application (Spring Boot)

Add REST API

👩‍💻 Author

Christy josie
