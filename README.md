# 🚀 Spring Boot User Management REST API

A beginner-friendly **Spring Boot REST API** project that demonstrates how to build CRUD (Create, Read, Update, Delete) operations using Java and Spring Boot.

This project focuses on understanding RESTful API development, HTTP methods, HTTP status codes, `ResponseEntity`, and the Spring Boot application lifecycle. Instead of using a database, it uses an **in-memory HashMap** to simplify learning the backend fundamentals.

---

# 📌 Project Objectives

* Learn REST API development using Spring Boot
* Understand HTTP request-response lifecycle
* Practice CRUD operations
* Learn how `ResponseEntity` works
* Understand HTTP Status Codes
* Explore Spring Boot startup lifecycle
* Build a foundation before learning Spring Data JPA and MySQL

---

# ✨ Features

* ✅ Create User
* ✅ Update Existing User
* ✅ Delete User
* ✅ Retrieve All Users
* ✅ RESTful API Design
* ✅ ResponseEntity with HTTP Status Codes
* ✅ In-Memory Storage using HashMap
* ✅ CommandLineRunner Example
* ✅ ApplicationRunner Example
* ✅ Beginner-friendly project structure

---

# 🛠️ Technologies Used

| Technology    | Version            |
| ------------- | ------------------ |
| Java          | 17                 |
| Spring Boot   | 4.x                |
| Maven         | Latest             |
| IntelliJ IDEA | IDE                |
| REST API      | HTTP               |
| HashMap       | In-Memory Database |

---

# 📂 Project Structure

```text
src
├── main
│   ├── java
│   │   └── com.demo.first
│   │       ├── FirstApplication.java
│   │       ├── HelloController.java
│   │       ├── AppStartupRunner.java
│   │       ├── AppArgsRunner.java
│   │       └── app
│   │           ├── User.java
│   │           └── UserController.java
│   └── resources
└── test
```

---

# 🌐 REST API Endpoints

| HTTP Method | Endpoint     | Description          |
| ----------- | ------------ | -------------------- |
| GET         | `/api/hello` | Returns Hello World  |
| GET         | `/api/user`  | Returns Sample User  |
| POST        | `/user`      | Create New User      |
| PUT         | `/user`      | Update Existing User |
| DELETE      | `/user/{id}` | Delete User          |
| GET         | `/user`      | Get All Users        |

---

# 📨 Sample JSON Request

### Create User

```json
{
  "id": 1,
  "name": "Ravi",
  "email": "ravi620bd@gmail.com"
}
```

---

# ✅ Sample JSON Response

```json
{
  "id": 1,
  "name": "Ravi",
  "email": "ravi620bd@gmail.com"
}
```

---

# 📖 Spring Boot Concepts Covered

* Spring Boot Starter
* REST Controller
* Request Mapping
* GET Mapping
* POST Mapping
* PUT Mapping
* DELETE Mapping
* RequestBody
* PathVariable
* ResponseEntity
* HttpStatus
* POJO (Plain Old Java Object)
* HashMap
* Collections Framework
* ApplicationRunner
* CommandLineRunner

---

# 📡 HTTP Status Codes Used

| Status Code        | Meaning                           |
| ------------------ | --------------------------------- |
| **200 OK**         | Request processed successfully    |
| **201 Created**    | New resource created successfully |
| **204 No Content** | Resource deleted successfully     |
| **404 Not Found**  | Requested resource not found      |

---

# 🧠 Learning Outcomes

Through this project, I learned:

* REST API Development
* CRUD Operations
* Spring Boot Fundamentals
* HTTP Methods
* HTTP Status Codes
* ResponseEntity
* Java Collections
* In-Memory Data Management
* Spring Boot Application Lifecycle
* Clean Project Structure

---

# 🚀 Future Improvements

* MySQL Database Integration
* Spring Data JPA
* Hibernate ORM
* Bean Validation
* Global Exception Handling
* Logging (SLF4J / Logback)
* Swagger / OpenAPI Documentation
* Spring Security
* JWT Authentication
* Docker Containerization
* Unit Testing (JUnit)
* Integration Testing
* CI/CD using GitHub Actions
* Deployment on AWS / Render / Railway

---

# 📷 API Testing

This project can be tested using:

* Postman
* IntelliJ HTTP Client
* cURL
* Thunder Client (VS Code)

---

# 📚 Next Version

* User Login API
* Registration API
* Password Encryption (BCrypt)
* JWT Authentication
* Role-Based Authorization
* MySQL Integration
* Complete User Management System

---

# 👨‍💻 Author

**Ravi Ranjan**

Java Backend Developer (Learning)

### Skills

* Java
* Spring Boot
* REST APIs
* Maven
* Git & GitHub
* IntelliJ IDEA

⭐ If you found this project useful, feel free to star the repository and connect with me on LinkedIn.
