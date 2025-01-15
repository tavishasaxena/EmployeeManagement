# Employee Management System

This project is an Employee Management System developed using a microservice architecture with Spring Boot. It consists of a backend for managing employee data and a frontend for user interaction. The system includes functionalities such as CRUD operations for employees and service discovery enabled through Eureka.

---

## Backend

The backend is built using **Spring Boot** and follows a **microservice architecture**. It is divided into multiple services, each responsible for specific functionalities. These services communicate via REST APIs. The backend employs **Spring Data JPA** for database operations and **Eureka** for service discovery.

### Key Features:
- **Employee CRUD Operations**: Create, Read, Update, and Delete employee data.
- **Service Discovery with Eureka**: Facilitates automatic service discovery.
- **Database Integration**: Uses H2 (or a database of your choice).
- **Security**: (Add details if authentication/authorization is implemented).

### Technologies Used:
- **Spring Boot** for backend services.
- **Spring Data JPA** for database interactions.
- **Spring Cloud Eureka** for service discovery.
- **H2 Database** (or other databases like MySQL, PostgreSQL).

---

## Frontend

The frontend is developed using **React** (or your preferred frontend framework). It communicates with the backend via REST APIs to manage employee data.

### Key Features:
- **User Interface**: Responsive UI for managing employee data.
- **Forms**: Allows users to add, edit, and delete employees.
- **API Integration**: Interacts with backend APIs to fetch and update employee data.

### Technologies Used:
- **React** for frontend development.
- **Axios** or **Fetch API** for API calls.
- **Bootstrap** or **Tailwind CSS** for styling.

---

## Running the Project

### Backend
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the backend folder:
   ```bash
   cd backend
   ```
3. Run the Spring Boot application:
   ```bash
   ./mvnw spring-boot:run
   ```

The backend will be accessible at `http://localhost:8080`.

### Frontend
1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the frontend:
   ```bash
   npm start
   ```

The frontend will be accessible at `http://localhost:3000`.

---




