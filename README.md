# Notes App 
**Notes management + Backend + CRUD + RestFul API**

A backend-focused REST API built using Java and Spring Boot to manage user notes.
This project demonstrates backend fundamentals including API design, database
integration, validation, and layered architecture.

---

## Tech Stack
- Java
- Spring Boot 
- MySQL
- Spring Data JPA
- Maven
- Postman

---

## Features
- Create a new note
- Fetch all notes
- Delete a note by ID
- RESTful API design
- Backend input handling and error scenarios
- Database persistence using MySQL
- and many more features are coming 

---

## API Endpoints

| Method | Endpoint        | Description            |
|------|-----------------|------------------------|
| GET  | /api/notes      | Fetch all notes        |
| POST | /api/notes      | Create a new note      |
| DELETE | /api/notes/{id} | Delete note by ID     |

---

## Project Architecture

The application follows a clean layered architecture:

- **Controller Layer**  
  Handles HTTP requests and responses

- **Service Layer**  
  Contains business logic and validations

- **Repository Layer**  
  Manages database interactions using JPA

- **Model Layer**  
  Defines database entities

This separation ensures maintainability, scalability, and testability.

---

## Database Design

- Relational database using MySQL
- Auto-generated primary keys
- Persistent storage for notes data
- Validated data flow between API and database

---

## How to Run Locally

1. Clone the repository  
2. Configure MySQL credentials in `application.properties`  
3. Create a database named `notes_db`  
4. Run the Spring Boot application  
5. Test APIs using Postman or any REST client  

---

## What I Learned

- Designing REST APIs using Spring Boot
- Structuring backend applications using controller–service–repository pattern
- Integrating MySQL with Spring Data JPA
- Handling backend validations and data persistence
- Understanding real-world backend workflows

---

## Future Improvements

- User authentication and authorization
- Update note functionality
- Pagination and sorting
- Exception handling and custom error responses
- Unit and integration tests

---

## Author

Khushbu
Aspiring Backend / Java Developer  

