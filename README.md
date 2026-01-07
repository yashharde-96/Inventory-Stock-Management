# 📦 Inventory Management System – Backend API

## 🔍 Project Overview
This project is a backend-only Inventory Management System developed using Spring Boot. It provides secure and scalable RESTful APIs for managing users, roles, products, carts, and orders. The system implements JWT-based authentication, role-based access control (RBAC), and email-based OTP verification during user registration and password recovery. All APIs are tested using Postman and documented with Swagger.

## 🚀 Features
- User Registration with Email OTP Verification
- Secure Login using JWT Authentication
- Role-Based Access Control (ADMIN, DEALER, CUSTOMER)
- Product Management (CRUD APIs)
- Cart Management (Add, Update, View Cart)
- Password Encryption using BCrypt
- Forgot Password & Reset Password using OTP
- OTP Expiry Handling
- Swagger API Documentation

## 🏗️ Project Architecture
- Controller Layer
- Service Layer
- Repository Layer
- DTO & Mapper Layer
- Security Layer (JWT + Spring Security)

## 🛠️ Technologies Used
- Language: Java
- Frameworks: Spring Boot, Spring Security
- ORM: Hibernate, JPA
- Database: MySQL
- Authentication: JWT, BCrypt
- Email Service: JavaMailSender (Gmail SMTP)
- API Documentation: Swagger (Springdoc OpenAPI)
- Build Tool: Maven
- Testing Tool: Postman

## 🔐 Authentication Flow
1. User registers and receives OTP on email
2. User verifies OTP and account gets activated
3. Login generates JWT token
4. JWT token used to access secured APIs
5. Role-based authorization applied

## 📬 API Documentation
Swagger UI:
http://localhost:8080/swagger-ui.html

## ▶️ How to Run
1. Clone the repository
2. Import into IntelliJ IDEA or STS
3. Configure MySQL and email credentials
4. Run the application
5. Test APIs using Postman or Swagger

## 📌 Note
- Backend-only project
- No frontend framework used
- Suitable for API integration with any frontend

## 👨‍💻 Author
Yash Harde
Backend Developer | Java | Spring Boot | REST APIs
