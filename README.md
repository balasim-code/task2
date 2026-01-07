# Product Management REST API  
**Spring Boot Backend System**

---

## 1. Introduction

This project is a **Spring Boot–based RESTful web service** developed to demonstrate the fundamental principles of backend application development, REST architecture, and layered system design.

The system provides a simple **Product Management API** that allows clients to perform Create, Read, Update, and Delete (CRUD) operations on product resources. It is intended for academic and learning purposes, focusing on proper architectural separation, maintainability, and clarity.

---

## 2. Objectives of the Project

The main academic objectives of this project are to:

- Understand the structure of a Spring Boot application  
- Implement RESTful web services using Spring Web  
- Apply layered architecture (Controller, Service, Repository)  
- Practice CRUD operations with a database  
- Demonstrate separation of concerns in backend systems  
- Understand request/response handling using DTOs  

---

## 3. Scope of the System

The system allows users (clients) to:

- Add new products  
- Retrieve all products  
- Retrieve a product by its ID  
- Update existing product details  
- Delete products from the system  

The project focuses only on backend development. No graphical user interface (GUI) is included.

---

## 4. Technologies and Tools Used

- **Java** – Programming language  
- **Spring Boot** – Application framework  
- **Spring Web** – REST API development  
- **Spring Data JPA** – Data persistence layer  
- **Hibernate** – ORM framework  
- **H2 / MySQL** – Database system  
- **Maven** – Dependency and project management tool  

---

## 5. System Architecture

Client → Controller → Service → Repository → Database

---

## 6. Project Structure

(See project folders for controller, service, repository, model, and dto packages.)

---

## 7. API Endpoints

GET `/products` – Retrieve all products  
GET `/products/{id}` – Retrieve product by ID  
POST `/products` – Create a new product  
PUT `/products/{id}` – Update an existing product  
DELETE `/products/{id}` – Delete a product  

---

## 8. How to Run the System

Run `DemoApplication.java` and access the system via `http://localhost:8080`.

---

## 9. Learning Outcomes

Students gain practical experience in REST API development, layered architecture, and backend system design.

---

## 10. Future Enhancements



<img width="1908" height="1068" alt="database" src="https://github.com/user-attachments/assets/dbf02fb6-77bf-42bb-9cd8-9cec6188882d" />


Security integration, validation, logging, and frontend development.

