
Employee Management System

Overview

The **Employee Management System** is a web-based application designed to manage employee data efficiently. It supports CRUD operations (Create, Read, Update, Delete) with role-based access control. The system is built using a microservices architecture to ensure modularity, scalability, and robustness.

This project integrates a **Java Spring Boot backend** and an **Angular frontend**, providing a seamless and user-friendly interface for managing employee records. The backend handles business logic and serves REST APIs, while the frontend interacts with the backend to display and manipulate data.



Features and Functionalities

### Core Features

1. **Role-Based Access Control**:
   - **Admin**: Full access to create, view, update, and delete employee records.
   - **User**: Restricted access to view employee records only.

2. **Employee Operations**:
   - Add Employee
   - View Employee Details
   - Edit Employee Details
   - Delete Employee Records

3. **User Interface**:
   - Intuitive UI for smooth navigation.
   - Search employees by ID, name, or email.
   - Sort records in ascending/descending order.
   - Paginated display of employee records.

4. **Security**:
   - Authentication and authorization using JSON Web Tokens (JWT).
   - Secured API endpoints based on roles.

---

## Technologies Used

### Frontend:
- **Angular**: For a responsive and interactive user interface.
- **Bootstrap/Material Design**: For UI components and styling.

### Backend:
- **Spring Boot**: Java-based REST API to manage business logic.
- **H2 Database**: Lightweight in-memory database for development and testing.

### Additional Tools:
- **Docker**: For containerized microservices deployment.
- **AWS**: Cloud deployment with scaling and monitoring.
- **CI/CD Pipelines**: For automated testing and deployment.

---

## Architecture

The application uses a **Client-Server Architecture** with a microservices-based backend.

- **Frontend**: 
  - Angular application that communicates with REST APIs via HTTP.
  - Provides a user-friendly interface for operations.
  
- **Backend**:
  - Spring Boot REST APIs handle business logic and data processing.
  - H2 Database used for data storage.

- **Communication**:
  - All interactions between the frontend and backend are conducted using JSON over HTTP/HTTPS.

---

## Setup and Installation

### Prerequisites
- Java 11 or higher
- Node.js and npm
- Angular CLI
- Docker (optional for containerized deployment)

### Steps

#### Backend (Spring Boot)
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/employee-management-system.git
   ```
2. Navigate to the backend directory:
   ```bash
   cd employee-management-system/backend
   ```
3. Build and run the Spring Boot application:
   ```bash
   ./mvnw spring-boot:run
   ```

#### Frontend (Angular)
1. Navigate to the frontend directory:
   ```bash
   cd employee-management-system/frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the Angular development server:
   ```bash
   ng serve
   ```

#### Docker Deployment
1. Build Docker images for both the backend and frontend.
2. Use `docker-compose` to set up the application:
   ```bash
   docker-compose up
   ```

---

## Deployment Details

- **Hosting Platform**: AWS
- **Containerization**: Dockerized backend and frontend for efficient deployment.
- **CI/CD**: Integrated pipelines for automated builds and deployments.

---

## Future Enhancements
- Migrate to a production-grade database (e.g., MySQL, PostgreSQL).
- Add analytics dashboards for enhanced reporting.
- Implement email notifications for employee updates.
- Extend multi-language support for a global audience.

---

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contributors
- [Harsh Singh](https://github.com/harsh-982/SDE-majorproject)
