# Spring Microblog
A small microblog application, that allows users to register, leave posts and comment them. Application is built with Spring Framework (no Spring Boot), with PostgreSQL as database choice and deployed on Tomcat servlet container, v. 9 (https://tomcat.apache.org/download-90.cgi). 

Interaction with the system is supported via a web interface (html with Thymeleaf and Bootstrap) and a REST API (implemented for certain entities of the applciation). Postman collections are also provided for testing the REST API, data access is set in db.properties (postgresql connection) and war deployment directory in pom.xml. Integration tests are also provided to provide sufficient REST API code coverage (JUnit).

Spring Data JPA, Hibernate, Spring MVC, Spring Security, REST, JUnit 5 
