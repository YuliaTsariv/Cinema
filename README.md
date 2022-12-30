# :film_strip: Taxi-service :film_strip:

### 📜 Project description:
This project provide  example how to create WEB Application using Java Spring, Java Hibernate, JDBC and MySQL as relation database. The basic functionality provide most common operations with objects such as Cinema Hall, Movie, Ticket, User, Shopping Cart, Order. REST API, and Basic Authentication allow use this application like endpoint third party applications for managing Cinema service.The app supports registration, authentication and CRUD operations.

### Technologies
- JDK 17
- Hibernate
- Spring
- [MySQL](https://www.mysql.com/)
- Maven
- JDBC
- [Apache Tomcat](https://tomcat.apache.org/)

### Available endpoints:
- POST: /register - all

- GET: /cinema-halls - user/admin

- POST: /cinema-halls - admin

- GET: /movies - user/admin

- POST: /movies - admin

- GET: /movie-sessions/available - user/admin

- POST: /movie-sessions - admin

- PUT: /movie-sessions/{id} - admin

- DELETE: /movie-sessions/{id} - admin

- GET: /orders - user

- POST: /orders/complete - user

- PUT: /shopping-carts/movie-sessions - user

- GET: /shopping-carts/by-user - user

- GET: /users/by-email - admin
### Installation process
- Install IntelliJ IDEA (Ultimate Edition) with maven
- Create new project, use menu File -> New -> Project from Version Control copy past
- and insert git url [https://github.com/YuliaTsariv/Cinema.git]
- Install [MySQL](https://www.mysql.com/) and create empty database
- Edit configuration in [db.properties](src/main/resources/db.properties) file.
- Install [Apache Tomcat](https://tomcat.apache.org/) 9.0.65
- Add Tomcat to Run/Debug configuration of project

The program will create the first user automatically.
<br/>Role: ADMIN
<br/>Email: admin@i.ua
<br/>Password: admin123

### UML Models Diagram
<p align="center"><img src="/img/Hibernate_Cinema_Uml.png"></p>


