
## Employee CRUD Operation Full Stack Project

# Project Overview

This project is a Full Stack Employee Management System that performs CRUD (Create, Read, Update, Delete) operations on employee records. It uses Spring Boot for the backend and React for the frontend, with MySQL as the database.

# Features

Add new employees

View employee list

Update employee details

Delete employee records

User authentication and authorization

Tech Stack

# Frontend:

React.js

HTML, CSS


# Backend:

Spring Boot (Java)

Spring Data JPA

REST APIs

# Database:

MySQL

Setup Instructions

Backend Setup

# Clone the repository:

git clone https://github.com/yourusername/EmployeeCrudOperationFullStackProject.git

# Navigate to the backend directory:

cd backend

# Configure application.properties (MySQL credentials):

spring.datasource.url=jdbc:mysql://localhost:3306/employeedb
spring.datasource.username=root
spring.datasource.password=yourpassword

# Run the application:

mvn spring-boot:run

# Frontend Setup

Navigate to the frontend directory:

cd frontend

Install dependencies:

npm install

Start the React application:

npm start

# API Endpoints

Method              Endpoint                Description

GET                 /employees              Get all employees

POST                /employees              Add new employee

GET                 /employees/{id}         Get employee by ID

PUT                 /employees/{id}         Update employee

DELETE              /employees/{id}         Delete employee

# Future Enhancements

Implement JWT authentication

Add search and filter functionality

Improve UI with Material UI

# Author

Krunal Ivolkar

GitHub: kivolkar