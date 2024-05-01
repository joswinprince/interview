## Interview

1. What is Spring Boot, and how does it differ from the Spring framework?
   > Spring boot is  a java based open source framework used to build production grade stand alone spring based application. It provides a streamlined way to setup and develop spring application by offering a convention over configuration approach.
spring boot is built on top of spring framework and offers several advantages over traditional spring applications.
- Simplified configuration
- Embedded server
- Standalone application
- Opinionated Defaults
- production ready features
- Integrated Development Experience:

2. Features:?
- Embedded servlet container
- Auto configuration: automatically configures based on the dependencies present in class path.
- spring boot actuator: provides a built in production ready feature for monitoring and managing applications.
- Test support: unit testing, integration testing , end to end testing.
- Spring Boot Starter: Spring Boot provides a collection of starter dependencies that simplify the setup of various components and frameworks (e.g., Spring MVC, Spring Data, Spring Security). Starter dependencies include all the necessary dependencies and configuration to get started with a specific feature or technology.

3. Spring mvc ?
> Spring MVC simplifies the development of web applications in Java by providing a robust and flexible framework for handling HTTP requests and responses. It follows the MVC architectural pattern, which separates an application into three main components:
- Model: Model represents the data and business logic of the application.
- View: Renders the user interface based on the data provided by the model.
- Controller: Controller acts as intermediary between model and view, handling user input and update the model accordingly.
  
4. Spring Data:
> Spring Data is a powerful tool for simplifying database access in Java applications, promoting consistency, and enabling developers to work with various data stores using a unified programming model.
- Spring Data JPA
- Spring Data Mongodb 
- Spring Data JDBC
- Spring Data Redis

5. Spring Data JPA:
> Spring Data JPA is a part of the larger Spring Data project, specifically designed to simplify the development of data access layer in Java applications that use the Java Persistence API (JPA) for interacting with relational databases.
- Repository abstraction: It provides repository abstraction on top of JPA allowing developers to define interfaces for database operations, without implementing them.Spring Data JPA automatically generates the necessary implementation at runtime based on method signatures, reducing boilerplate code.
- Query methods:  Developers can define query methods in repository interfaces using method naming conventions. Spring Data JPA interprets these method names and generates the corresponding JPQL (Java Persistence Query Language) queries, making it easy to perform common CRUD (Create, Read, Update, Delete) operations without writing SQL queries manually.
- Pagination and sorting: Spring Data JPA supports pagination and sorting out of the box, allowing developers to retrieve data in chunks and specify sorting criteria easily.
- Auditing: It provides built-in support for auditing, allowing developers to automatically track who created or modified an entity and when it was created or modified.
- Derived queries: In addition to query methods based on method naming conventions, developers can also define custom queries using JPA's @Query annotation or query derivation from method names.
- Specification: Spring Data JPA supports the Specification pattern, enabling developers to define dynamic queries based on certain criteria at runtime.
- conclusion: Overall, Spring Data JPA simplifies database access in Java applications by providing a high-level abstraction for common data access operations, reducing the amount of boilerplate code, and promoting consistency across data access layer implementations.


6. 

