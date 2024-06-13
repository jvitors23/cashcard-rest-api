# CashCard Rest API

Spring boot web application implementing simple CRUD rest API for managing cashcards. 

Project from [Building a REST API with Spring Boot](https://spring.academy/courses/building-a-rest-api-with-spring-boot) spring academy course.

# Endpoints

* POST ```/cashcards/```: Creates a new cashcard
* GET ```/cashcards/```: List all cashcards
* GET ```/cashcards/{id}```: Retrieves cashcard
* PUT ```/cashcards/{id}```: Updates cashcard
* DELETE ```/cashcards/{id}```: Deletes cashcard

## Running the project

You can run the project by executing:

```
./gradlew bootRun
```

The application will be available on [http://localhost:8080/](http://localhost:8080/)

## Running tests

To run tests, use:

```
./gradlew test
```

## Technologies

- [Java](https://www.java.com/en/)
- [Gradle](https://gradle.org/)
- [Spring Boot](https://spring.io/projects/spring-boot)
  - [Spring Web](https://docs.spring.io/spring-boot/reference/web/index.html)
  - [Spring Data](https://spring.io/projects/spring-data)
  - [Spring Security](https://spring.io/projects/spring-security)
- [Junit](https://junit.org/junit5/)
