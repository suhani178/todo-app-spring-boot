# Todo App — Spring Boot

A web-based task management application developed using Spring Boot. The application enables users to manage daily tasks through a web interface, demonstrating core concepts of Spring MVC, Spring Data JPA, database integration, and server-side rendering with Thymeleaf.

## Features:

- **Task Management:** Create, view, and delete tasks.
- **Task Status Management:** Update task status as supported by the application.
- **Database Integration:** Persist task data using MySQL.
- **MVC Architecture:** Separate application logic into controller, service, and repository layers.
- **Dynamic Web Interface:** Render application pages using Thymeleaf.
- **Data Persistence:** Use Spring Data JPA and Hibernate for database operations.

## Technology Stack:

| Category | Technology |
|---|---|
| Programming Language | Java |
| Backend Framework | Spring Boot |
| Web Framework | Spring MVC |
| Persistence | Spring Data JPA |
| ORM | Hibernate |
| Database | MySQL |
| Frontend | HTML, CSS, Thymeleaf |
| Build Tool | Maven |
| Development Environment | IntelliJ IDEA |

## Project Structure:

    todo-app-spring-boot/
    ├── src/
    │   └── main/
    │       ├── java/
    │       │   └── com/app/todoapp/
    │       │       ├── controller/
    │       │       ├── model/
    │       │       ├── repository/
    │       │       ├── service/
    │       │       └── TodoappApplication.java
    │       └── resources/
    │           ├── templates/
    │           │   └── tasks.html
    │           └── application.properties
    ├── pom.xml
    └── README.md

## Prerequisites:

Ensure the following software is installed:

- Java Development Kit (JDK)
- MySQL Server
- IntelliJ IDEA or another Java IDE
- Maven, if not using the Maven Wrapper

## Getting Started:

### 1. Clone the Repository

    git clone https://github.com/suhani178/todo-app-spring-boot.git

### 2. Open the Project

Open the cloned repository in IntelliJ IDEA and allow Maven to import the project and resolve its dependencies.

### 3. Configure the Database

Create a MySQL database for the application.

Configure the database connection in `src/main/resources/application.properties` using your local database settings.

Keep database credentials private. If the application uses environment variables, configure the required variables in your IDE's run configuration. Never commit passwords or other secrets to version control.

### 4. Run the Application

Run the `TodoappApplication.java` main class from your IDE.

Alternatively, execute the following command from the project root:

    mvn spring-boot:run

### 5. Access the Application

Open the following address in your browser after the application starts:

    http://localhost:8080

## Key Concepts Demonstrated:

- Spring Boot application configuration
- Model–View–Controller (MVC) architecture
- Dependency injection
- Separation of controller, service, and repository responsibilities
- Database operations using Spring Data JPA
- Object-relational mapping with Hibernate
- Dynamic HTML rendering using Thymeleaf
- Maven dependency management

## Future Enhancements:

- Task deadlines and priority levels
- Task search and filtering
- User authentication and authorization
- Responsive UI improvements
- Task completion filters

## Author:

**Suhani Kumari**

GitHub: https://github.com/suhani178

## License:

This project is intended for educational and portfolio purposes.
