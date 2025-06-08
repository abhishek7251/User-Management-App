# User Management System

A simple user management system that loads data from [dummyjson.com/users](https://dummyjson.com/users), stores it in an in-memory database, and provides a UI for searching users by first name, last name, and SSN. Clicking on a user displays detailed information.

## Features

- Fetch users from an external API
- Store user data in an in-memory database
- Search users by first name, last name, and SSN
- Display user details on selection
- Built with Angular (Frontend) and Spring Boot (Backend)

## Repository Structure

```
user-management-app/
├── user-mngt-frontend-app/    # Angular application with Angular Material
├── user-management-app-backend/     # Spring Boot backend with in-memory database
├── README.md    # This file
└── ...
```

## Prerequisites

- Node.js v20.12.2(for frontend)
- Angular CLI 15.2.1
- Java 17+ (for backend)
- Maven 3.9.9(for backend dependencies)
- Spring Boot v3.4.2

## Installation & Running

1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd repo-root
   ```

2. Start the backend:
   ```sh
   cd backend
   ./mvnw spring-boot:run
   ```
   The backend will be available at `http://localhost:8080/`.

3. Start the frontend:
   ```sh
   cd frontend
   npm install
   ng serve
   ```
   The frontend will be available at `http://localhost:4200/`.

## API & Functionality

- Fetch users from `https://dummyjson.com/users` at startup
- Store in a local in-memory database (backend)
- Search users by first name, last name, or SSN (frontend UI)
- Clicking on a user displays their full details

## License

This project is licensed under the MIT License.

