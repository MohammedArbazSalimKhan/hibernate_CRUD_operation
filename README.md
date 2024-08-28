# Student Management System - CRUD Operations

This project demonstrates a simple Student Management System using Hibernate ORM with MySQL. It performs basic CRUD (Create, Read, Update, Delete) operations on a `Student` entity.

## Project Structure

```plaintext
src/
├── main/
│   ├── java/
│   │   ├── com/
│   │   │   ├── sms/
│   │   │   │   ├── App.java              # Main application class
│   │   │   │   ├── entity/
│   │   │   │   │   └── Student.java      # Student entity class
│   │   │   │   └── util/
│   │   │   │       └── HibernateUtil.java # Hibernate utility class for session factory
│   ├── resources/
│   │   └── hibernate.cfg.xml             # Hibernate configuration file
└── test/
Prerequisites
Java Development Kit (JDK) 8 or later
Apache Maven
MySQL Server
MySQL JDBC Driver
Setup Instructions
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/student-management-system.git
cd student-management-system
Database Setup

Open your MySQL client or MySQL Workbench.

Create a new database:

sql
Copy code
CREATE DATABASE studenthibernatedb;
Configure Hibernate

Open the src/main/resources/hibernate.cfg.xml file.

Ensure that your MySQL username and password are correct:

xml
Copy code
<property name="hibernate.connection.username">root</property>
<property name="hibernate.connection.password">your_password</property>
The configuration file should already be set up to connect to the studenthibernatedb database and map the Student entity.
