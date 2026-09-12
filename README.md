# 👩‍💻 Employee Management System (Spring MVC)

[![Java](https://img.shields.io/badge/Java-17-blue?logo=java&logoColor=white)](https://www.java.com/) 
[![Maven](https://img.shields.io/badge/Maven-3.9.0-red?logo=apache-maven&logoColor=white)](https://maven.apache.org/) 
[![MySQL](https://img.shields.io/badge/MySQL-8.0-blue?logo=mysql&logoColor=white)](https://www.mysql.com/) 
[![Spring](https://img.shields.io/badge/Spring-MVC-green?logo=spring&logoColor=white)](https://spring.io/projects/spring-framework)

---
## 📝 Project Overview
The **Employee Management System** is a web application built using **Spring MVC**, **Hibernate**, and **MySQL**.  
It allows admins to manage employees with features like **Add, Update, Delete, and Search employees**, and provides **login functionality** for admin access.

---

## ✨ Features
- 🔑 Admin login and authentication  
- ➕ Add employee records  
- ✏️ Update employee records  
- ❌ Delete employee records  
- 🔍 Search employee records  
- 🖥️ JSP-based user interface with navigation  
- 🗄️ Hibernate ORM for database interaction  
- 📦 Maven-based project for easy build and dependency management  

---

---

## 🛠️ Technology Stack
| Layer | Technology |
|-------|------------|
| Backend | Java, Spring MVC, Hibernate |
| Frontend | JSP, HTML, CSS |
| Database | MySQL |
| Build Tool | Maven |
| IDE | Eclipse |
| Version Control | Git/GitHub |

---

## 📂 Project Structure
```
EmployeeManagementSystem/
│
├── src/main/java/ → Java classes (Controllers, Services, Repositories, POJOs)
├── src/main/webapp/ → JSP pages, images, CSS
├── src/main/resources/ → persistence.xml, configuration files
├── pom.xml → Maven build file
├── .gitignore → Git ignore rules
└── README.md → Project documentation
```
## 🗂️ ER Diagram

```text
+----------------+        +----------------+
|     Admin      |        |   Employee     |
+----------------+        +----------------+
| admin_id (PK)  |◄────── | emp_id (PK)    |
| username       |        | name           |
| password       |        | email          |
+----------------+        | department     |
                          | designation    |
                          | salary         |
                          +----------------+

Relationship:
- One Admin can manage multiple Employees (1-to-many)
```

---

## 🚀 Setup Instructions
1. **Clone the repository**  
```bash
git clone https://github.com/Shruti627/EmployeeManagementSystem.git
```

**Import into Eclipse**
```
File → Import → Existing Maven Project → Select cloned folder

Right-click project → Run As → Maven build or Run on server (Tomcat)

Access in browser: http://localhost:8080/EmployeeManagementSystem/

```
## 🔮 Future Enhancements
- Role-based access (Admin vs Employee)
- Integration with Spring Security for authentication
- REST APIs for CRUD operations

## 👩‍🎓 Author
**Shruti P. Sangvikar** – Third-year Engineering Student
