# Employee Management System

This repository contains two implementations of an Employee Management System (EMS):

1. **Angular + Spring Boot**
2. **React + Spring Boot**

Both implementations use a Spring Boot backend for handling RESTful APIs and employ Angular/React for the frontend. The goal of this repository is to showcase proficiency in both Angular and React, as well as demonstrate the ability to work with a full-stack Java Spring Boot application.

## Project Structure

The repository is structured as follows:


- **`angular-springboot/`**: Contains the Angular-based frontend project that interacts with the backend for managing employees.
- **`react-springboot/`**: Contains the React-based frontend project that interacts with the same backend for managing employees.
- **`backend/`**: The Spring Boot backend code that provides REST APIs for both the Angular and React frontends.

## Setup and Installation

### Prerequisites:
- Java (JDK 8 or higher)
- Node.js and npm
- Maven (for backend Spring Boot)

### 1. Backend (Spring Boot):

1. Navigate to the `backend` directory:
    ```bash
    cd backend
    ```

2. Install dependencies and run the Spring Boot application:
    ```bash
    mvn spring-boot:run
    ```

The backend will be running on `http://localhost:8080`.

### 2. Frontend (Angular version):

1. Navigate to the `angular-springboot` directory:
    ```bash
    cd angular-springboot
    ```

2. Install Angular dependencies:
    ```bash
    npm install
    ```

3. Run the Angular application:
    ```bash
    ng serve
    ```

The Angular frontend will be running on `http://localhost:4200`.

### 3. Frontend (React version):

1. Navigate to the `react-springboot` directory:
    ```bash
    cd react-springboot
    ```

2. Install React dependencies:
    ```bash
    npm install
    ```

3. Run the React application:
    ```bash
    npm start
    ```

The React frontend will be running on `http://localhost:3000`.

## Features:

- **Employee CRUD operations**: Add, Update, Delete, and View Employee records.
- **Authentication**: Simple login functionality to manage access to employee data.
- **REST API**: Backend exposes a set of RESTful APIs for interacting with employee data.

## Why Two Frontends?

The purpose of having both Angular and React implementations is to demonstrate my proficiency in both frameworks, showcasing versatility in frontend development. Recruiters can assess my ability to work with different frontend technologies and integrate them with a common backend.

---

Feel free to explore the individual `README.md` files in each project for more specific instructions and details.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Angular + Spring Boot - Employee Management System

This project demonstrates an Employee Management System using **Angular** for the frontend and **Spring Boot** for the backend.

## Features:
- User login and authentication
- CRUD operations on employee data
- Integration with Spring Boot backend for managing employee records

## Setup:
1. Ensure the backend Spring Boot application is running on `http://localhost:8080`.
2. Navigate to the `angular-springboot` directory:
    ```bash
    cd angular-springboot
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Run the Angular application:
    ```bash
    ng serve
    ```
   The frontend will be available at `http://localhost:4200`.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# React + Spring Boot - Employee Management System

This project demonstrates an Employee Management System using **React** for the frontend and **Spring Boot** for the backend.

## Features:
- User login and authentication
- CRUD operations on employee data
- Integration with Spring Boot backend for managing employee records

## Setup:
1. Ensure the backend Spring Boot application is running on `http://localhost:8080`.
2. Navigate to the `react-springboot` directory:
    ```bash
    cd react-springboot
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Run the React application:
    ```bash
    npm start
    ```
   The frontend will be available at `http://localhost:3000`.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Spring Boot - Employee Management System Backend

This is the backend part of the Employee Management System built using **Spring Boot**. It exposes RESTful APIs to handle employee data and is used by both the Angular and React frontends.

## Features:
- CRUD operations for employee data
- Simple user authentication

## Setup:
1. Navigate to the `backend` directory:
    ```bash
    cd backend
    ```
2. Run the Spring Boot application:
    ```bash
    mvn spring-boot:run
    ```
3. The backend will be available at `http://localhost:8080`.







Employee-Management-System/
│
├── angular-springboot/           # Angular frontend + Spring Boot backend
│   ├── e2e/                      # End-to-end test files
│   ├── src/
│   │   ├── app/
│   │   │   ├── create-employee/         # Create employee component
│   │   │   ├── employee-details/        # Employee details component
│   │   │   ├── employee-list/           # Employee list component
│   │   │   ├── update-employee/         # Update employee component
│   │   │   ├── app-routing.module.ts    # Routing module
│   │   │   ├── app.component.ts         # Root component
│   │   │   ├── app.module.ts            # Main app module
│   │   │   ├── employee.service.ts      # Service for handling employee data
│   │   │   └── employee.ts              # Employee model
│   │   ├── assets/
│   │   ├── environments/
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── main.ts
│   │   ├── polyfills.ts
│   │   ├── styles.css
│   │   └── test.ts
│   ├── angular.json
│   ├── karma.conf.js
│   ├── package-lock.json
│   ├── package.json
│   ├── tsconfig.app.json
│   ├── tsconfig.json
│   ├── tsconfig.spec.json
│   ├── tslint.json
│   ├── .gitignore
│   └── README.md                # Angular frontend documentation
│
├── react-springboot/             # React frontend + Spring Boot backend
│   ├── public/
│   ├── src/
│   ├── .gitignore
│   ├── package-lock.json
│   ├── package.json
│   └── README.md                # React frontend documentation
│
├── backend/                     # Spring Boot Backend (shared by both Angular and React projects)
│   ├── .mvn/
│   ├── src/
│   ├── .gitignore
│   ├── mvnw
│   ├── mvnw.cmd
│   ├── pom.xml                 # Maven dependencies
│   └── README.md               # Spring Boot backend documentation
└── README.md                    # Main repository README with project overview
