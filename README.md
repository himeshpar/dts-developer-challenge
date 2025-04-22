# DTS Developer Technical Test – HMCTS Case Management System

This is my submission for the HMCTS Case Management Coding Challenge. It includes a backend API built with Spring Boot that allows caseworkers to manage their tasks effectively.

## ✨ Features

- Create, retrieve, update, and delete tasks
- Task properties:
  - `title` (required)
  - `description` (optional)
  - `status`: `NOT_STARTED`, `IN_PROGRESS`, `DONE`
  - `dueDate` (must be in the future)
- Data stored in an H2 in-memory database
- Swagger/OpenAPI ready (optional)
- Includes validation and error handling

## 🔧 Tech Stack

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Maven

## ▶️ Running the App

1. Clone the repository  
   ```bash
   git clone https://github.com/himeshpar/dts-developer-challenge.git
   cd dts-developer-challenge
