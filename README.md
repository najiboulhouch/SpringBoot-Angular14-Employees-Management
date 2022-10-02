# Online Employee Management Web Application

#### A full-stack Online Employees Management web application using Spring Boot 2.7 and Angular 14. 
This is a Single Page Appliaction with client-side rendering. It includes [backend]() and [frontend]() two seperate projects on different branches.

#### Live Demo: [https://employeemanagementfrontapp.herokuapp.com/](https://employeemanagementfrontapp.herokuapp.com/)


## Features
- REST API
- JWT authentication
- Cookie based visitors
- Persistent users information
- Employee & Payment management
- Function
- Leave
- Authentication
- Pagination
- Form Validation
- Template-Driven-form
## Technology Stacks
**Backend**
  - Java 11
  - Spring Boot 2.7
  - Spring Security
  - JWT Authentication
  - Spring Data JPA
  - Hibernate
  - PostgreSQL
  - MySQL
  - Maven

**Frontend**
  - Angular 14
  - Angular CLI
  - Bootstrap


## How to  Run

Start the backend server before the frontend client.  

**Backend**

  1. Install [PostgreSQL](https://www.postgresql.org/download/)  or [MySQL](https://www.mysql.com/fr/downloads/)
    2. Configure datasource in `application.yml`.
  3. `cd EmployeeManBackend`.
  4. Run `mvn install`.
  5. Run `mvn spring-boot:run`.
  6. Spring Boot will import mock data into database by executing `import.sql` automatically.
  7. The backend server is running on [localhost:8081]().

**Frontend**
  1. Install [Node.js and npm](https://www.npmjs.com/get-npm)
  2. `cd EmployeeManFrontend`.
  3. Run `npm install`.
  4. Run `ng serve`
  5. The frontend client is running on [localhost:4200]().
  
Note: The backend API url is configured in `src/environments/environment.ts` of the frontend project. It is `localhost:8081/api/v1` by default.


