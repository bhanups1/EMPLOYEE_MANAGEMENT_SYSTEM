# Employee Management System

The **Employee Management System (EMS)** is a Java-based desktop application that demonstrates the use of **Object-Oriented Programming (OOPs)** concepts along with **MySQL Workbench** for data storage.  
It provides a simple and effective way to manage employee records such as adding, updating, deleting, and viewing details.


---

## 🚀 Features
- Add new employees with details (ID, Name, Department, Salary, etc.)
- View employee information in a structured format
- Update existing employee details
- Delete employee records
- Secure login system (Admin/User)
- Integration with **MySQL Workbench** using **JDBC**

---

## 🛠️ Tech Stack
- **Programming Language:** Java (OOP concepts: Encapsulation, Inheritance, Polymorphism, Abstraction)
- **Database:** MySQL Workbench
- **Connector:** JDBC (Java Database Connectivity)
- **IDE (Optional):** IntelliJ IDEA / Eclipse / NetBeans

---


EMPLOYEE MANAGEMENT SYSTEM/
│── .idea/
│── out/
│── src/
│   └── employee.management.system/
│       ├── AddEmployee.java
│       ├── conn.java
│       ├── InternEmployee.java
│       ├── Login.java
│       ├── Main_class.java
│       ├── RemoveEmployee.java
│       ├── Splash.java
│       ├── UpdateEmployee.java
│       ├── View_Employee.java
│       └── icons/
│── .gitignore
│── EMPLOYEE MANAGEMENT SYSTEM.iml

----

This tells me your project has:

Splash screen (Splash.java)
Login system (Login.java)
CRUD operations (AddEmployee, View_Employee, UpdateEmployee, RemoveEmployee)
Database connection (conn.java)
Main entry (Main_class.java)
Icons folder for images/gifs

----


## 📂 Project Structure
EMPLOYEE MANAGEMENT SYSTEM/
│── src/
│ └── employee.management.system/
│ ├── AddEmployee.java # Add new employees
│ ├── conn.java # Database connection file
│ ├── InternEmployee.java # Handles intern-specific records
│ ├── Login.java # Login authentication system
│ ├── Main_class.java # Entry point of the project
│ ├── RemoveEmployee.java # Delete employee records
│ ├── Splash.java # Splash screen (front.gif)
│ ├── UpdateEmployee.java # Update existing records
│ ├── View_Employee.java # Display employee details
│ └── icons/ # Contains UI images/icons
│── .gitignore
│── EMPLOYEE MANAGEMENT SYSTEM.iml

---

## 🚀 Features
- User-friendly **GUI with Java Swing**
- **Login System** (Admin authentication)
- Add new employees with full details
- View employee data in tabular format
- Update employee details
- Remove employees from database

  
- **Intern Employee module**
- Splash screen on startup

---

## 🛠️ Tech Stack
- **Java (Swing, OOPs concepts)**
- **MySQL Workbench** for database
- **JDBC** (Java Database Connectivity)
- **IDE:** IntelliJ IDEA / Eclipse / NetBeans

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Employee_Management_System.git
cd Employee_Management_System


----
2. Setup MySQL Database

Open MySQL Workbench

Create a database:

CREATE DATABASE employee_db;


Create table:

CREATE TABLE employees (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    role VARCHAR(50),
    department VARCHAR(50),
    salary DECIMAL(10,2),
    email VARCHAR(100) UNIQUE
);

3. Configure Database Connection

In conn.java, update your MySQL credentials:

String url = "jdbc:mysql://localhost:3306/employee_db";
String user = "root";        // your MySQL username
String password = "password"; // your MySQL password

4. Run the Application

Open project in IntelliJ/Eclipse

Add MySQL Connector JAR to classpath

Run Main_class.java

🎯 OOP Concepts Used

Encapsulation: Employee fields with getters & setters

Inheritance: Employee types (Full-time, Intern)

Polymorphism: Overloaded methods for employee operations

Abstraction: DAO-like structure for database connection

📸 Screenshots

Splash Screen

Login Page

Employee Dashboard

(👉 You can add your actual screenshots here)

👨‍💻 Author

Bhanu Partap
📧 bhanupartap947247@gmail.com

🔗 LinkedIn  
 | GitHub


---

⚡ This version matches your **exact folder structure** and explains each `.java` file.

