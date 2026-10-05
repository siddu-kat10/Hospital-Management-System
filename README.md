**Hospital Management System**

 **Project Overview**
The Hospital Management System is a backend web application developed using Java and Spring Boot to streamline and manage essential hospital operations. The system provides functionality for managing patients, doctors, appointments, and billing information in an organized and efficient manner.

The application follows the MVC architecture, providing a clear separation between the presentation, business logic, and data access layers. RESTful APIs are implemented using Spring Web, while Spring Data JPA is used to perform database operations.

**Features**

1.Patient registration and management
2.Doctor registration and management
3.Appointment scheduling and management
4.Patient, doctor, and appointment CRUD operations
5.Billing information management
6.RESTful API implementation
7.MySQL database integration
8.Entity relationships using JPA
9.API testing using Postman
10.Layered MVC architecture

**🛠️ Technologies Used**

Java
Spring Boot
Spring Web
Spring Data JPA
Hibernate
MySQL
Maven
Postma
HTML & CSS

**🏗️ Architecture**

The application follows a layered MVC-based architecture:

**Controller → Service → Repository → Database**

Controller: Handles HTTP requests and provides REST API endpoints.
Service: Contains the application's business logic.
Repository: Uses Spring Data JPA to communicate with the database.
Entity: Represents database tables and defines relationships between entities.

**🗄️ Database**

The application uses MySQL for persistent data storage. JPA relationships such as One-to-Many and Many-to-One are used to establish relationships between patients, doctors, and appointments while maintaining data consistency.

**🔗 API Operations**

The system supports standard CRUD operations:

POST – Create new records
GET – Retrieve records
PUT – Update existing records
DELETE – Delete records

The APIs were tested using Postman to verify request handling, responses, and database operations.

▶️ How to Run

1.Clone the repository.
2.Import the project into Eclipse or Spring Tool Suite.
3.Configure the MySQL database.
4.Update the database credentials in application.properties.
5.Run the Spring Boot application.
6.Use Postman to test the REST APIs.

**🎯 Objective**

The main objective of this project is to demonstrate practical knowledge of Java, Spring Boot, REST APIs, Spring Data JPA, Hibernate, MySQL, MVC architecture, and CRUD operations while building a real-world hospital management application.
