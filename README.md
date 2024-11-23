# Spring Project: Spring Series

## Table of Contents
1. [What is Spring?](#what-is-spring)
2. [Project for Spring Series](#project-for-spring-series)
3. [Prerequisite and Tools Required for Spring](#prerequisite-and-tools-required-for-spring)
4. [IoC and DI](#ioc-and-di)
5. [What is Spring Boot?](#what-is-spring-boot)
6. [DI using Spring Boot](#di-using-spring-boot)
7. [Autowire using Spring Boot](#autowire-using-spring-boot)
8. [Spring without Boot](#spring-without-boot)
9. [Spring XML Configuration](#spring-xml-configuration)
10. [Constructor and Setter Injection](#constructor-and-setter-injection)
11. [Autowire in Spring](#autowire-in-spring)
12. [Need for Spring Boot MVC](#need-for-spring-boot-mvc)
13. [Spring Boot Web](#spring-boot-web)
14. [Spring MVC and Layers](#spring-mvc-and-layers)
15. [Spring Web HTTP Methods (GET, PUT)](#spring-web-http-methods-get-put)
16. [Spring Web Update and DELETE](#spring-web-update-and-delete)
17. [Spring Data JPA](#spring-data-jpa)
18. [Spring Data JPA and H2 Setup](#spring-data-jpa-and-h2-setup)
19. [Spring Data JPA with JPA Repository](#spring-data-jpa-with-jpa-repository)
20. [Understanding React Frontend](#understanding-react-frontend)
21. [Project Setup with Model](#project-setup-with-model)
22. [Loading Data in H2](#loading-data-in-h2)
23. [CORS Error in Spring Boot](#cors-error-in-spring-boot)
24. [Response Entity and GetByID](#response-entity-and-getbyid)
25. [Add Product with Image](#add-product-with-image)
26. [Fetching Image](#fetching-image)
27. [Update and Delete](#update-and-delete)
28. [Search Feature](#search-feature)

---

## What is Spring?
Spring is a powerful framework for building Java applications, particularly for creating enterprise-level applications. It is lightweight, flexible, and offers comprehensive infrastructure support for developing Java-based applications. 

The core of Spring focuses on **dependency injection (DI)** and **aspect-oriented programming (AOP)**, simplifying the development of Java applications and promoting better modularity and testing.

---

## Project for Spring Series
This project demonstrates a hands-on approach to learning and applying the concepts from the Spring Framework. It includes various features, tools, and functionalities such as **Spring Boot**, **Spring Data JPA**, and **React** for frontend integration.

---

## Prerequisite and Tools Required for Spring
Before starting, ensure that the following tools and technologies are installed:
- **Java** (JDK 8 or higher)
- **Spring Tool Suite (STS)** or **IntelliJ IDEA** or **Eclipse** (IDE of choice)
- **Maven** or **Gradle** (for dependency management)
- **MySQL** or **H2** (database)
- **Node.js** (for React setup, if using React as frontend)
- **React** (for frontend integration)

---

## IoC and DI
- **Inversion of Control (IoC)** is a design principle where the control of object creation and dependency management is shifted from the application code to a container (Spring Container).
- **Dependency Injection (DI)** is a specific form of IoC where objects are passed their dependencies at runtime, allowing for better testability and modularity.

---

## What is Spring Boot?
Spring Boot is an extension of the Spring framework that simplifies the setup and development of Spring-based applications. It eliminates much of the boilerplate configuration required by Spring, allowing developers to create standalone, production-ready applications with minimal effort.

---

## DI using Spring Boot
In Spring Boot, Dependency Injection is implemented automatically through annotations such as `@Autowired`. Spring Boot manages all the beans and their dependencies in the background.

Example:
```java
@Autowired
private MyService myService;
