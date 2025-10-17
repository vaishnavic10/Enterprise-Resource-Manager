# 🏢 Enterprise Resource Manager

**Enterprise Resource Manager** is a **Java-based console application** that enables organizations to efficiently manage **employee records** using **CRUD operations**. This project leverages **JDBC** to connect with a **MySQL database** and follows the **DAO (Data Access Object) pattern** for clean and modular database interaction.

---

## 📋 Features

-  **Add Employee:** Create a new employee record with **ID, Name, and Salary**  
-  **View Employees:** Retrieve and display all employee records  
-  **Update Employee:** Update employee details (e.g., Name) using **Employee ID**  
-  **Delete Employee:** Remove an employee record by **ID**  
-  **DAO Pattern:** Ensures modular and maintainable database operations  
-  **Menu-Driven Interface:** Simple console-based navigation for user interaction  

---

## 🛠 Tech Stack

| Component | Technology |
|-----------|------------|
| **Language** | Java |
| **Database** | MySQL |
| **Connectivity** | JDBC |
| **IDE** | Eclipse / IntelliJ / VS Code (any Java IDE) |

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/EnterpriseResourceManager.git
```
## Set up MySQL database:

- Create a database, e.g., employee_db

- Create a table employees with fields id, name, salary
```bash
CREATE DATABASE employee_db;
USE employee_db;
CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    salary DOUBLE
);
```
---

Configure JDBC connection in DBConnection.java with your MySQL credentials.

- Run the Application:

- Open the project in your Java IDE

- Run App.java

- the menu-driven interface to perform CRUD operations
  
---

## 📈 Project Highlights

- ✅ Demonstrates database connectivity using JDBC

- ✅ Implements clean architecture via DAO pattern

- ✅ Provides efficient console-based employee management

- ✅ Can be extended to integrate GUI or web-based
  
---
