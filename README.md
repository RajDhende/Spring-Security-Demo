# 🔐 Spring Security Demo

A minimal yet powerful **Spring Boot** application demonstrating **JWT-based authentication** with **Spring Security**.

---

## 📌 Overview

This project showcases how to **secure REST API endpoints using JSON Web Tokens (JWT)**. Key features include:

- ✅ Custom login endpoint that generates a JWT on successful authentication
- 🔒 Secured REST endpoints protected via JWT
- 🧰 JWT token validation and filtering
- 🛠️ In-memory **H2 Database** for testing
- 💡 Clean and extensible Spring Security configuration

---

## 🧰 Tech Stack

- ☕ Spring Boot
- 🔐 Spring Security
- 🔑 JWT (Java JWT)
- 🗄️ H2 Database
- 🧪 Maven

---

## ⚙️ Configuration Notes

* 🔑 **JWT secret key** and **token expiration time** are defined in `application.properties`.
* 📝 **Logging** is enabled for easier development and debugging.
* 🌍 **CORS configuration** can be added or updated in `SecurityConfig.java` as required.

---


## 📁 Project Structure

```bash
Spring-Security-Demo/
├── .idea/
├── .mvn/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/security_demo/
│   │   │       ├── jwt/
│   │   │       │   ├── AuthEntryPointJwt.java
│   │   │       │   ├── AuthTokenFilter.java
│   │   │       │   ├── JwtUtils.java
│   │   │       │   ├── LoginRequest.java
│   │   │       │   └── LoginResponse.java
│   │   │       ├── GreetingsController.java
│   │   │       ├── SecurityConfig.java
│   │   │       └── SecurityDemoApplication.java
│   │   └── resources/
│   │       ├── static/
│   │       ├── templates/
│   │       ├── application.properties
│   │       └── schema.sql
│   └── test/
├── target/
├── .gitattributes
├── .gitignore
├── HELP.md
├── mvnw
├── mvnw.cmd
└── pom.xml                        
└── README.md
```



## 👤 Demo User

Use the following credentials to log in:

- **Username:** `raj`
- **Password:** `1234`

---

## 🚀 Getting Started

1. 📦 **Install dependencies** (Maven will do this automatically if using an IDE like IntelliJ or Eclipse)
2. ▶️ **Run the application** by launching the `SecurityDemoApplication` class (`main` method)

---

## 🌐 Access the Application

* ▶️ **API Base URL:** [http://localhost:8080](http://localhost:8080)
* 🧪 **H2 Console:** [http://localhost:8080/h2-console](http://localhost:8080/h2-console)

> 💡 **Use the JDBC URL from `application.properties` (e.g.,** `jdbc:h2:mem:testdb` **)**
---



