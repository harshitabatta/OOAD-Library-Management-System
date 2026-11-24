# Library Management System 📚

A Java-based Library Management System developed as part of an **Object-Oriented Analysis and Design (OOAD)** project. The application follows the MVC architecture and uses Spring Boot with MySQL for backend development and database management.

## 📌 About the Project

This project explores the development of a library management application using Java and the Spring Boot framework. It is structured around the MVC (Model-View-Controller) architecture, with MySQL used for database storage.

The project focuses on applying object-oriented design principles, Java backend development, database integration, and the Spring Boot application structure.

## 🛠️ Tech Stack

- **Programming Language:** Java
- **Backend Framework:** Spring Boot
- **Architecture:** Model-View-Controller (MVC)
- **Database:** MySQL
- **Frontend:** HTML, CSS
- **Build Tool:** Maven

## 📂 Project Structure

```text
OOAD-Library-Management-System/
│
├── library/
│   ├── src/
│   ├── target/
│   ├── pom.xml
│   └── application.properties
│
├── mysql/
│
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Java JDK
- Maven
- MySQL
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/OOAD-Library-Management-System.git
   ```

2. Navigate to the application directory:

   ```bash
   cd OOAD-Library-Management-System/library
   ```

3. Configure your database connection in:

   ```text
   src/main/resources/application.properties
   ```

   Update the database URL, username, and password according to your local MySQL configuration.

4. Build the project:

   ```bash
   mvn clean install
   ```

5. Run the Spring Boot application:

   ```bash
   mvn spring-boot:run
   ```

6. Access the application through the local URL configured by Spring Boot, typically:

   ```text
   http://localhost:8080
   ```

## 🏗️ Architecture

The application follows the **Model-View-Controller (MVC)** architectural pattern:

- **Model:** Represents application data and business entities.
- **View:** Handles the user interface using HTML.
- **Controller:** Handles requests and coordinates application logic.

This architecture helps separate application responsibilities and makes the project easier to organize and maintain.

## 🗄️ Database

The project uses **MySQL** for database management.

Database configuration is maintained through the Spring Boot application properties file.

## 🎓 Project Context

- **Project:** Library Management System
- **Subject:** Object-Oriented Analysis and Design (OOAD)
- **Language:** Java
- **Framework:** Spring Boot
- **Architecture:** MVC

## 📚 Concepts Explored

- Object-Oriented Programming
- MVC Architecture
- Java Backend Development
- Spring Boot Application Development
- Database Connectivity
- MySQL
- Maven Build Management

## 👩‍💻 Author

**Harshita Batta**

---

An academic project exploring object-oriented design and Java-based web application development.
