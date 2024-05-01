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
- Actuator security: 
spring boot provides access to restrict production grade management endpoints which can be secured using spring security based on roles or permissions.

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


6. Key features of Spring MVC include:
- POJO-based: Controllers and other components in Spring MVC are Plain Old Java Objects (POJOs), making them easy to test and maintain.
- Annotation-based configuration: Spring MVC allows configuring controllers, request mappings, and other components using annotations, reducing XML configuration.
- Flexible data binding: Supports various data binding techniques, including form handling and validation.
- Interceptors: Provides interceptors for pre-processing and post-processing of requests and responses.
- View resolution: Supports different view technologies such as JSP, Thymeleaf, FreeMarker, etc.
- RESTful support: Spring MVC provides support for building RESTful web services alongside traditional web applications.

7. Key principles of RESTful web services include:
- Resource-based: In RESTful architecture, resources are identified by unique URIs (Uniform Resource Identifiers), and each resource can be manipulated using standard HTTP methods (GET, POST, PUT, DELETE, etc.). Resources represent entities such as users, products, or orders.
- Uniform interface: RESTful services have a uniform interface, which means that clients interact with resources through a consistent set of HTTP methods and standardized representations of resources (e.g., JSON or XML).
- Statelessness: RESTful services are stateless, meaning that each request from a client to the server must contain all the necessary information to process the request. The server does not store any client state between requests.
Client-server architecture: RESTful systems are based on a client-server architecture, where clients and servers are separate entities that communicate over a network using HTTP protocols. This separation of concerns allows for scalability and flexibility.
- Cacheability: Responses from RESTful services can be cached to improve performance and reduce server load. HTTP caching mechanisms can be utilized to specify caching policies for resources.
- Layered system: RESTful architectures can be composed of multiple layers, where each layer performs a specific function. This layered approach promotes scalability and simplifies the architecture by separating concerns.
