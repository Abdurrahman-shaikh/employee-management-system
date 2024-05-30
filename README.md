# Employee Management System

This project is an Employee Management System built using Spring Boot for the backend and React for the frontend. The backend API provides CRUD (Create, Read, Update, Delete) operations for managing employee records.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [API Endpoints](#api-endpoints)
- [Running the Application](#running-the-application)
- [Built With](#built-with)
- [Contributing](#contributing)
- [Authors](#authors)
- [License](#license)

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Java 8 or higher
- Maven
- Node.js and npm
- Spring Boot
- React

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/employee-management-system.git
   ```

2. **Backend Setup:**

   Navigate to the project directory and build the Spring Boot application:

   ```bash
   cd employee-management-system/backend
   mvn clean install
   ```

3. **Frontend Setup:**

   Navigate to the frontend directory and install the dependencies:

   ```bash
   cd ../frontend
   npm install
   ```

## API Endpoints

### Get All Employees

- **URL:** `/api/v1/employees`
- **Method:** `GET`
- **Description:** Retrieve a list of all employees.

### Create Employee

- **URL:** `/api/v1/employees`
- **Method:** `POST`
- **Description:** Create a new employee.
- **Request Body:**
  ```json
  {
    "firstName": "John",
    "lastName": "Doe",
    "emailId": "john.doe@example.com"
  }
  ```

### Get Employee by ID

- **URL:** `/api/v1/employees/{id}`
- **Method:** `GET`
- **Description:** Retrieve an employee by their ID.

### Update Employee

- **URL:** `/api/v1/employees/{id}`
- **Method:** `PUT`
- **Description:** Update an existing employee's details.
- **Request Body:**
  ```json
  {
    "firstName": "John",
    "lastName": "Doe",
    "emailId": "john.doe@example.com"
  }
  ```

### Delete Employee

- **URL:** `/api/v1/employees/{id}`
- **Method:** `DELETE`
- **Description:** Delete an employee by their ID.

## Running the Application

1. **Start the Backend:**

   Navigate to the backend directory and run the Spring Boot application:

   ```bash
   cd backend
   mvn spring-boot:run
   ```

2. **Start the Frontend:**

   Navigate to the frontend directory and start the React application:

   ```bash
   cd frontend
   npm start
   ```

3. **Access the Application:**

   Open your browser and go to `http://localhost:3000` to access the Employee Management System.

## Built With

- [Spring Boot](https://spring.io/projects/spring-boot) - Backend framework
- [React](https://reactjs.org/) - Frontend library

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## Authors

- **Abdur Rahman** - [Abdurrahman-shaikh](https://github.com/Abdurrahman-shaikh)
---

