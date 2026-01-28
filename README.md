# Football Stats Explorer – Spring Boot API

A RESTful backend application built with **Spring Boot** and **PostgreSQL** for managing and querying football player statistics.  
This API serves structured and filterable player data, making it easy to build dashboards, analytics tools, or frontend applications on top of it.

🔗 Repository:  
https://github.com/NisargMakwana142/Football-Stats-Explorer-Spring-Boot-API

---

## 🧠 Project Overview

The **Football Stats Explorer API** provides a clean and scalable backend service to:
- Store football player statistics
- Retrieve and filter player data using REST APIs
- Follow industry-standard backend architecture
- Serve as a foundation for frontend or analytics applications

The project is structured using **Spring Boot best practices** with clear separation of concerns.

---

## 🏗️ Architecture Used

This project follows the **Model–Repository–Service–Controller (MRSC)** architecture:

- **Model (Entity Layer)**  
  Represents the database schema using JPA entities.

- **Repository Layer**  
  Handles database interactions using Spring Data JPA.

- **Service Layer**  
  Contains business logic and acts as an intermediary between controllers and repositories.

- **Controller Layer**  
  Exposes RESTful endpoints and handles client requests.

This architecture ensures:
- Clean code separation
- Better maintainability
- Easier debugging and testing
- Scalability for future features

---

## 📌 Key Features

✔ Get all players data  
✔ Filter players by:
- Team (`/players?team=Arsenal`)
- Position (`/players?position=gk`)
- Nation (`/players?nation=England`)
- Name (`/players?name=Rashford`)  
✔ Combined filtering (e.g., team + position)  
✔ Clean JSON responses  
✔ Structured backend design following layered architecture

---

## 🛠️ Tech Stack

- **Java 21**
- **Spring Boot**
- **Spring Data JPA**
- **Hibernate ORM**
- **PostgreSQL**
- **Maven**
- **RESTful API design**

