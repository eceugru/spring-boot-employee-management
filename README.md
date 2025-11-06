# Spring Boot Employee Management CRUD Application

A simple web application built with **Spring Boot**, **Spring MVC**, **Thymeleaf**, **JPA**, and **MySQL**.  
It allows users to perform CRUD (Create, Read, Update, Delete) operations on employee records through a web interface.

## 🚀 Run Locally
1. Configure your MySQL database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/employee_directory
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   spring.jpa.hibernate.ddl-auto=update
