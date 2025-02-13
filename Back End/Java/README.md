# Spring Boot Roadmap

## Introduction
This roadmap is designed to guide you through the fundamentals of Spring Boot and backend development, from beginner to advanced levels. Each stage is thoughtfully structured with specific goals, curated resources, and hands-on tasks to ensure practical learning.

Created and Prepared By [Mohamed Zkrallah](https://github.com/muhammadzkralla).


## Criteria
- Three Levels: Beginner, Intermediate, and Advanced, with a focus on building strong fundamentals before progressing to advanced topics.
- Practical Approach: Tasks are abstracted for brevity, with more details available in Notion.
- Bonuses: Bonuses are included for deeper learning. They are not optional, don’t skip them entirely, do them later if you don't have time then. Most bonuses will be already discussed in later weeks.
- AI-Assisted Learning: Feel free to use AI to explore topics further but avoid relying on it to complete tasks or write code for you.
- Time Interval: Some topics can not be finished in just one week, try to learn as much as you can and get back later.
- Self-Learning & Research: As you progress to the advanced level, expect to do more self-learning and independent research. Not everything will be spoon-fed with resources. Developing the ability to learn on your own, read documentation, and experiment with implementations is crucial.
- Quick Tip: I beleive in learning by building. Build what you want to learn and learn from what you build. Do not just study theory, but implement what you have learned in a project or even a simple program.


---

# Level 1: Beginner (Weeks 1–10)

Focus:
* Version control using Git & GitHub.
* Basic knowledge of HTML, CSS, and JavaScipt for the Front-end.
* The OSI Model, specially, the application layer and HTTP internals.
* Java programming language and OOP (Object-Oriented Programming) in Java.
* Prerequisites for Spring Boot.
* Introduction to Spring Boot and Spring MVC.
* Introduction to Database sytems and RDBMS (MySQL Server & PostgreSQL).
* Introduction to ORMs and Spring Data JPA.


---

## Week 1: Introduction to Version Control with Git

Topics:
* Git basics
* GitHub
* Branches
* Commits
* Pull requests

Resources:

- [Git and GitHub for Beginners (FreeCodeCamp.org)](https://www.youtube.com/watch?v=RGOj5yH7evk)
- [Git and GitHub Tutorial for Beginners (Kevin Stratvert)](https://www.youtube.com/watch?v=tRZGeaHPoaw)
- [Git and Github (Big Data)](https://www.youtube.com/watch?v=Q6G-J54vgKc)


Task: Set up a GitHub repository and upload the student management system.

Bonus: Learn about Date Formatting.

## Week 2: Basic HTML, CSS, and JS for the Front-end

Topics:
* HTML
* CSS
* JavaScipt
* Basic Front-end Knowledge

Resources:

- [HTML5 and CSS3 (SuperSimpleDev)](https://youtu.be/G3e-cpL7ofc?si=nkOWX7S6EwYhBta1)
- [HTML5 and CSS3 (FreeCodeCamp.org)](https://youtu.be/mU6anWqZJcc?si=1MvHczhsZxkgS_pO)
- [JavaScipt Basics (Mosh)](https://youtu.be/W6NZfCO5SIk?si=B2J2hKqugXf_sTS1)
- [Build a Simple Portfolio Front-end (WEB CIFAR)](https://youtu.be/ZFQkb26UD1Y?si=UR4FNhijugBQzV_u)
- [Build a Simple To-Do List Front-end (Web Dev Simplified)](https://youtu.be/W7FaYfuwu70?si=PJpssoprYNyUQp69)

Task: Build a simple front-end for a website of your choice (portfolio, to-do list app, blog, etc).

Bonus: Learn about Regex (Regular Expressions).


## Week 3: Basics of Web Development

Topics:
* HTTP internals
* REST APIs
* Introduction to backend development
* CCNA
* OSI model

Resources:
- [Network Fundamentals for Web Developers](https://www.youtube.com/playlist?list=PLCy5RQkQgvf4yaL-AMDO8rpAAi90sWfGl)
- [Cisco CCNA 200-301](https://www.youtube.com/playlist?list=PLF1hDMPPRqGxpYdo0ctaa7MxfOi9vjs1u)
- [OSI Layers (Metwally Labs)](https://youtu.be/A31bxOyj5mk?si=BbKU-ebPy2sD7LqB)
- [What is a REST API?](https://www.youtube.com/watch?v=-mN3VyJuCjM)
- [HTTP Internals (Zkrallah)](https://medium.com/@muhammad.heshamyt/http-internals-and-building-your-own-http-client-from-scratch-part-i-d62b1028408d)
- [HTTP Messages (MDN)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages)

Task: <br>
1- Write a document explaining how a REST API works and how clients and servers communicate through HTTP. <br>
2- Build a simple HTTP client program that performs GET, POST requests to some online fake API. <br>

Bonus: Learn about Postman API.

Note: Do not stop learning computer networking after this week. Computer networking is from the fundamentals of computer science, specially in backend.


## Week 4: Introduction to Programming

Topics:
* Java syntax
* Basics of programming
* Variables
* Loops
* Conditionals

Resources:

- [Java Basics Crash Course (FreeCodeCamp.org)](https://www.youtube.com/watch?v=GdzRzWymT4c&t=25s)
- [Java Beginners (Playlist by Bro Code)](https://www.youtube.com/playlist?list=PLZPZq0r_RZOOj_NOZYq_R2PECIMglLemc)
- [Java Basics (GeeksForGeeks)](https://www.geeksforgeeks.org/java/)


Task: <br>
1- Write simple programs like calculating the sum of numbers or finding the largest number in an array. <br>
2- Implement basic binary search in Java. <br>
3- Try to solve some Leetcode easy questions using Java. <br>


## Week 5: Object-Oriented Programming (OOP)

Topics:
* Classes
* Objects
* Abstraction
* Inheritance
* polymorphism
* Encapsulation

Resources:

- [Java OOP Concepts (GeeksforGeeks)](https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/)
- [Introduction to OOP (Mosh)](https://youtu.be/pTB0EiLXUC8?si=Cwy9pzQIeTAqdvuI)
- [Introduction to OOP (FreeCodeCamp.org)](https://youtu.be/SiBw7os-_zI?si=odVcb7Cx78TxrR0X)
- [OOP in Java (Adel Naseem)](https://youtube.com/playlist?list=PLCInYL3l2AagY7fFlhCrjpLiIFybW3yQv&si=okMB2Lf0kXE6I6No)


Task: <br>
1- Create a basic student management system with classes for Student and Course. <br>
2- Shapes Task <br>

Note: Do not stop learning OOP after this week. OOP is from the fundamentals of computer science. You should be learning OOP all the time, specially in Java.


## Week 6: Java Essentials for Spring Boot

Topics:
* Maven/Gradle
* Basic file I/O
* Java collections

Resources:

- [Spring Boot Build Tool Documentation](https://docs.spring.io/spring-boot/reference/using/build-systems.html#using.build-systems)
- [Maven in 10 minutes](https://www.youtube.com/watch?v=bBqxC43ASsM)
- [Introduction to Maven](https://www.youtube.com/watch?v=bSaBmXFym30)
- [Maven Tutorial (6:12~)](https://www.youtube.com/watch?v=Xatr8AZLOsE)
- [Apache Maven Tutorial (Baeldung)](https://www.baeldung.com/maven#introduction-3)
- [Maven (GeeksForGeeks)](https://www.geeksforgeeks.org/apache-maven/)
- [Java Files (W3Schools)](https://www.w3schools.com/java/java_files.asp)
- [Java Files (Coding With John)](https://www.youtube.com/watch?v=ScUJx4aWRi0)
- [Java Collections](https://www.youtube.com/watch?v=viTHc_4XfCA)

Task: Create a Java application to manage a library system using ArrayList.

Bonus: Learn about Java Generics and Callback functions.

Note: While it's okay to use either Maven or Gradle for both Java and Kotlin Spring Boot Projects, I recommend sticking with Maven as it's more easy to understand and work with than Gradle. Also it's more common to use Maven with Java projects and Gradle with Kotlin projects. Anyways, I recommend using Maven alawys (specially as long as you are a beginner).


## Week 7: Introduction to Spring Boot

Topics:
* Spring Boot overview and setup
* Basic annotations (@RestController, @GetMapping, @PostMapping)
* Spring MVC

Resources:

- [Spring Documentation](https://docs.spring.io/spring-framework/reference/)
- [Spring Boot Documentation](https://docs.spring.io/spring-boot/)
- [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service)
- [What is Spring Boot? (Telusko)](https://youtu.be/L0v_3MzC1io?si=-Zd_KV1llMlKtvm-)
- [Spring Boot Tutorial (Amigoscode)](https://www.youtube.com/watch?v=9SGDpanrc8U)

Task: Create a simple REST API to manage books.

Bonus: Learn about MULTIPART requests.

Note: Dependency Injection, Spring JPA, and some concepts are mentioned in this tutorial but we will go through the details of them in later weeks.


## Week 8: Database Basics with MySQL and PostgreSQL

Topics:
* What is a database?
* Introduction to SQL
* Introduction to PostgreSQL and MySQL Server
* Setting up the RDBMS
* Basic queries

Resources:

- [Database Introduction (ByteByteGo)](https://www.youtube.com/playlist?list=PLCRMIe5FDPsdnSszazqVIQFh99t1ExH19)
- [MySQL Tutorial 1 (Fireship)](https://youtu.be/Cz3WcZLRaWc?si=CfB3po-zsdlbV678)
- [MySQL Tutorial 2 (NetworkChuck)](https://youtu.be/xiUTqnI6xk8?si=iLejnmfNfXbcdYBF)
- [PostgreSQL Tutorial (FreeCodeCamp.org)](https://www.youtube.com/watch?v=SpfIwlAYaKk)
- [SQLZoo Interactive Quizes](https://sqlzoo.net/wiki/SQL_Tutorial)
- [PostgreSQL Tutorials (Neon)](https://neon.tech/postgresql/tutorial)

Task: <br>
1- Create a database for the book management system. <br>
2- Try to solve some easy SQL questions on HackerRank or Leetcode. <br>

Bonus: Learn about relationships and join statements.

Note: Do not stop learning database after this week. Database is from the the fundamentals of computer science, specially in backend.


## Week 9: Integrating Spring Boot with PostgreSQL & Spring Data JPA

Topics:
* Spring Data JPA ORM
* CRUD operations
* SQL and ORMs

Resources:

- [Spring Boot Data Access Documentation](https://docs.spring.io/spring-boot/reference/data/index.html)
- [Spring Data JPA Documentation](https://docs.spring.io/spring-data/jpa/reference/index.html)
- [Spring JPA Tutorial (Amigoscode)](https://www.youtube.com/watch?v=8SGI_XS5OPw&t=2364s)

Task: Enhance the book management system with a PostgreSQL database.

Bonus: Learn how to hot-reload a Spring Boot project.


## Week 10: Building a Student Management System

Project: Build a Student Management System with REST APIs and PostgreSQL.

### **Objectives**
- Build a RESTful API for managing students.
- Implement the `Student` and `Course` entities.
- Implement a **one-to-many** relationship between Students and Books.
- Implement a **many-to-many** relationship between Students and Courses (Bonus).
- Use **Spring Boot** with **Spring Data JPA** and **PostgreSQL**.

### **Endpoints**
- Create a new student `POST /students`
- Retrieve all students `GET /students`
- Retrieve a student by ID `GET /students/{id}`
- Update a student's details `PUT /students/{id}`
- Delete a student `DELETE /students/{id}`
- Same thing for books and courses.
- Assign a book to a student `POST /students/{studentId}/books/{bookId}`
- Retrieve the student who owns a book `GET /books/{bookId}/owner`
- Retrieve all books of a student `GET /students/{studentId}/books`
- Remove a book from a student `DELETE /students/{studentId}/books/{bookId}`
- Enroll a student in a course `POST /students/{studentId}/courses/{courseId}`
- Retrieve all students in a course `GET /courses/{courseId}/students`
- Retrieve all the courses of a student `GET /students/{studentId}/courses`
- Remove a student from a course `DELETE /students/{studentId}/courses/{courseId}`

Note: When a book or course is deleted, its association with any students should also be removed.


---

# Level 2: Intermediate (Weeks 11–25)

Focus:
* Spring Core concepts like IoC, DI, AOP, Resources, etc.
* Input validation, error handling, and testing (unit & integration).
* Middlewares and Spring Security.
* Pagination, filtering, Lombok, file uploads.
* Sending OTPs using SMTP servers and SMS.
* More about SQL databases and difference between JPA, Spring Data JPA, and Hibernate ORM.
* Introduction to NoSQL databases and MongoDB.
* Asynchronous programming, Reactive Spring Boot, Spring Data R2DBC, and Spring WebFlux.
* Caching mechanisms and Introduction to Redis cache.
* Real-time communication with WebSockets and streaming with WebRTC.


---

## Week 11: Spring Core (IoC & DI)

Topics:
* Inversion of Control & IoC Container
* Dependency Injection design pattern
* Beans and Bean lifecycle.
* Spring annotations (@Bean, @Component, @Configuration, etc)

Resources:

- [Spring IoC Documentation](https://docs.spring.io/spring-framework/reference/core/beans.html)
- [Dependency Injection (Yehia Tech)](https://youtu.be/ttza41X-O6k?si=gC4w2oNyL-0HUNTf)
- [Spring Beans and DI (Maaike)](https://www.youtube.com/watch?v=aS9SQITRocc)
- [Spring IoC & DI (Telusko)](https://youtu.be/5cRaQqQb14Q?si=LMnNJ8FzBxvzd5gj)
- [Dependency Injection in Spring Boot (Telusko)](https://youtu.be/9EoAXpjnsxM?si=3nXAy7l-UgAuiosv)
- [Autowire in Spring Boot (Telusko)](https://youtu.be/ET39IFffr24?si=HWPLKUybWdwse9jF)
- [Spring Configuration (Code Java)](https://www.youtube.com/watch?v=xP04pANWBxE)

Task: Apply what you understood to the Student Management System or revisit what you already did for dependency injection.

Bonus: Learn about Spring Profiles.


## Week 12: Validation and Error Handling

Topics:
* Input validation (@Valid, @NotNull, Optional<>)
* Custom exception handling (@ControllerAdvice)
* Global exception handling (@RestControllerAdvice, @ExceptionHandler)

Resources:

- [Spring Exceptions Documentation](https://docs.spring.io/spring-framework/reference/web/webmvc/mvc-controller/ann-exceptionhandler.html)
- [Spring ControllerAdvice Documentation](https://docs.spring.io/spring-framework/reference/web/webmvc/mvc-controller/ann-advice.html)
- [Spring Validation Documentation](https://docs.spring.io/spring-framework/reference/web/webmvc/mvc-controller/ann-validation.html)
- [Java Exceptions (Coding With John)](https://youtu.be/1XAfapkBQjk?si=C3_nKYdqbD0TmqNj)
- [Validation in Spring Boot (Java Techie)](https://youtu.be/gPnd-hzM_6A?si=RA7QdMFwXyiPaWYd)
- [Spring Exception Handling (CodeSnippet)](https://youtu.be/IdHHwZg3v58?si=twwo-oeASqVKvxmY)
- [Spring Input Validation (Fast & Simple Dev)](https://youtu.be/LItERTUC9y4?si=89VXDylJC7LmtE-W)

Task: Add validation to the Student Management System and create custom error messages for invalid inputs.

Bonus: Learn about CORS.


## Week 13: Testing in Spring Boot

Topics:
* Unit testing with JUnit and Mockito
* Integration testing with testcontainers
* API Documentation

Resources:

- [Spring Testing Documentation](https://docs.spring.io/spring-framework/reference/testing.html)
- [Spring Boot Testing Documentation](https://docs.spring.io/spring-boot/reference/testing/index.html)
- [Unit vs Int Testing Intro (Dan Vega)](https://youtu.be/pNiRNRgi5Ws?si=-SMzaUukHOHGe-97)
- [Spring Boot Unit Testing (Teddy)](https://youtube.com/playlist?list=PL82C6-O4XrHcg8sNwpoDDhcxUCbFy855E&si=mGi5nqRWf7j4My9c)
- [Spring Boot Testing (Amigoscode)](https://www.youtube.com/watch?v=Geq60OVyBPg)

Task: Write unit tests for services and controllers, and integration tests for the database layer.

Bonus: Learn about Swagger.


## Week 14: Filters & Interceptors, Lombok, Pagination & Filtering, File Uploads

Topics:
* Spring Boot Filters
* Spring Boot Interceptors
* Lombok Annotations
* Pagination & Filtering Data
* Uploading a File with MULTIPART Requests

Resources:

- [Spring Filters Documentation](https://docs.spring.io/spring-framework/reference/web/webmvc/filters.html)
- [Spring Interceptors Documentation](https://docs.spring.io/spring-framework/reference/web/webmvc/mvc-config/interceptors.html)
- [Spring Boot File Upload Documentation](https://spring.io/guides/gs/uploading-files)
- [Spring Filter Series (Sergey Tech)](https://youtube.com/playlist?list=PLrHjhj3I5M_ljv8s-Bejj4tbYPjOnjwQp&si=yugB_pYcNNg_Rpbb)
- [Spring Boot Interceptors (CodeSnippet)](https://youtu.be/fNMciZvDN6A?si=zPzkU_IPoglQFkBw)
- [Lombok Tutorial (Amigoscode)](https://youtu.be/z7bsNF2Dtf0?si=9U5U17NdttXdL33w)
- [Spring Boot File Upload & Download (Java Techie)](https://youtu.be/XUL60-Ke-L8?si=6Ri2ulOIQfBgVNN7)
- [Spring Boot File Upload & Download (Telusko)](https://youtu.be/JIWdBBtCrjM?si=_BwWlx7GBGuBOadD)
- [Pagination in Spring Boot (Teddy)](https://youtu.be/HJw8p4SIJSs?si=XnPFyoRk56kAKTyP)
- [Pagination and Sorting in Spring Boot (Java Techie)](https://youtu.be/Wa0GQwWwzJE?si=OaVGNiEQeosIwwnr)
- [How to Define a Spring Boot Filter (GeeksforGeeks)](https://www.geeksforgeeks.org/how-to-define-a-spring-boot-filter/)
- [How to Define a Spring Boot Interceptors (GeeksforGeeks)](https://www.geeksforgeeks.org/spring-boot-interceptor/)
- [Pagination and Sorting in Spring Data JPA (Baeldung)](https://www.baeldung.com/spring-data-jpa-pagination-sorting)
- [Spring Boot File Upload & Download (GeeksforGeeks)](https://www.geeksforgeeks.org/spring-mvc-implementing-file-uploads-and-downloads/)

Task: <br>
1- Add logging feature to the students' management system using filters once and using interceptors once. <br>
2- Add the pagination feature to the students' management system. <br>
3- Add lombok annotations to the students' management system. <br>
4- Create a simple Spring Boot application that allows users to upload files using multipart requests and stores them in the local file system (or database for learning purposes). <br>

Bonus: Take a look on `Firebase` and try to implement file upload & download feature using `Firebase` instead of the above ways.

Note: In these resources, uploaded files are either stored in a database or saved as local files on the server. However, in most cases, this is not the best approach. Typically, uploaded files should be stored in a cloud service provider such as `AWS` or `Firebase`, while only the file URL is saved in the database. We will cover this in more detail during the `Firebase` week.


## Week 15: Introduction to Spring Security (Part 1)

Topics:
* Authentication vs Authorization
* Basic Authentication
* Session-based authentication
* Role-based access control
* CORS

Resources:

- [Spring Security Documentation](https://docs.spring.io/spring-security/reference/index.html)
- [Spring Boot Security Documentation](https://docs.spring.io/spring-boot/reference/web/spring-security.html#web.security)
- [Authentication vs Authorization & Security Concepts (Java Brains)](https://www.youtube.com/watch?v=I0poT4UxFxE)
- [Spring Boot Basic Authentication (Lazy Programmer)](https://youtu.be/IeDxBpe8j64?si=yv6JxVN7muM4XL21)
- [Role-based Access Control (Lazy Programmer)](https://youtu.be/Wq3MZxBlVzI?si=tXLiV4Wcygg3z7af)
- [Spring Security (Lazy Programmer) (start from end to start)](https://youtube.com/playlist?list=PLOktGWstEblrgb_rNddv3HGaazetE3t1A&si=AjT0vZs2OOBOVoq1)
- [Spring Security Basics (Java Brains)](https://www.youtube.com/playlist?list=PLqq-6Pq4lTTYTEooakHchTGglSvkZAjnE)
- [CORS in Spring (Telusko)](https://www.youtube.com/watch?v=iC1a8cUzGgc)
- [session-based Authentication (Baeldung)](https://www.baeldung.com/spring-security-session)
- [Basic Authentication (Baeldung)](https://www.baeldung.com/spring-security-basic-authentication)

Task: <br>
1- Implement basic authentication in your Spring Boot application.
* Use httpBasic() in your security configuration.
* Test the secured endpoints using Postman. <br>

2- Implement session-based authentication.
* Configure formLogin() for session management.
* Use HttpSession to store user-specific data. <br>

3- Configure role-based access control (e.g., allow only admins to delete resources). <br>
4- Test the secured endpoints using Postman. <br>

Bonus: Learn about Lombok.

Note: I recommend the first part of Lazy Programmer's playlist for this week.


## Week 16: Spring Security (Part 2): JWT and OAuth2

Topics:
* JWT (JSON Web Tokens)
* OAuth2
* Custom security configurations

Resources:
- [Spring Security Documentation](https://docs.spring.io/spring-security/reference/index.html)
- [Spring Boot Security Documentation](https://docs.spring.io/spring-boot/reference/web/spring-security.html#web.security)
- [Spring Security (Lazy Programmer) (start from end to start)](https://youtube.com/playlist?list=PLOktGWstEblrgb_rNddv3HGaazetE3t1A&si=AjT0vZs2OOBOVoq1)
- [Spring Security Basics (Java Brains)](https://www.youtube.com/playlist?list=PLqq-6Pq4lTTYTEooakHchTGglSvkZAjnE)
- [JWT & OAuth2 with Spring Security (Telusko)](https://www.youtube.com/watch?v=oeni_9g7too)
- [JWT Authentication (Baeldung)](https://www.baeldung.com/spring-security-oauth-jwt)

Task: <br>
1- Implement JWT-based authentication in your Spring Boot application.
* Generate and validate JWTs.
* Add a refresh token mechanism for token renewal. <br>

2- Secure your REST APIs with role-based access using JWT. <br>
3- Integrate OAuth2 with a provider like Google or GitHub. <br>
4- Test the secured endpoints using Postman. <br>

Bonus: Learn about Filters in Spring Boot.

Note: I recommend watching the second part of Lazy Programmer's playlist and Telusko's video for this week.


## Week 17: Sending Messages to Users via E-mail & SMS

Topics:
* SMTP servers
* SMS messages
* OTPs (One Time Password)

Resources:

- [Setup Gmail SMTP Server](https://youtu.be/kTcmbZqNiGw?si=rHu155NGP6VkaAZ9)
- [Sending E-mails in Spring Boot](https://youtu.be/ugIUObNHZdo?si=V65zzbeGJxMLy7eP)
- [Spring Email (Baeldung)](https://www.baeldung.com/spring-email)
- [SMS via Twilio in Spring Boot (Amigoscode)](https://youtu.be/OuBttmaPlhM?si=ZzRaiO3Ufw-VvogN)

Task: <br>
1- Configure a Gmail SMTP and write the email sending service. <br>
2- Create a simple email verification service by sending an OTP to the given email. <br>

Bonus: Learn about pagination.


## Week 18: More SQL Databases and Hibernate ORM

Topics:
* Advanced SQL concepts
* Hibernate ORM
* Joins & relationships
* Aggregate functions

Resources:

- [Hibernate Documentation](https://docs.jboss.org/hibernate/orm/6.6/introduction/html_single/Hibernate_Introduction.html)
- [Spring Hibernate Documentation](https://docs.spring.io/spring-framework/reference/data-access/orm/hibernate.html)
- [Hibernate and JPA Tutorial (Marco)](https://youtu.be/xHminZ9Dxm4?si=O1FXR-ga9GZb8KtL)
- [SQL Joins Animated + Practice (Anton)](https://youtu.be/Yh4CrPHVBdE?si=NTskK_hzaFnPVUSo)
- [Learn SQL Joins (Decomplexify)](https://youtu.be/nivyaiCeWjs?si=orLEGaNaKXiWqL_i)
- [Aggregate Functions in SQL (Bro Code)](https://youtu.be/9HXJUGT-06w?si=rorP_uXiUKYTbPsG)
- [Aggregate Functions in SQL (Becoming a Data Scientist)](https://youtu.be/jcoJuc5e3RE?si=G2_n7MxtfF8koxPX)
- [Advanced Aggregate Functions in SQL (Becoming a Data Scientist)](https://youtu.be/nNrgRVIzeHg?si=Nav2epckJhLvgRYS)
- [Advanced SQL Tutorial (Mode Analytics)](https://mode.com/sql-tutorial)
- [SQL Aggregate Functions (W3Schools)](https://www.w3schools.com/sql/sql_count_avg_sum.asp)
- [SQLZoo Interactive Quizes](https://sqlzoo.net/wiki/SQL_Tutorial)

Task: Solve SQL problems on HackerRank or Leetcode.

Bonus: Learn how to design a database.

Note: It's important to understand the difference between `JPA`, `Hibernate`, and `Spring Data JPA`. `JPA` is a specification or an interface, `Hibernate` is an implementation of this interface and an ORM, and `Spring Data JPA` is a framework that relies on `JPA` implementations like `Hibernate` or any other implementation (but `Hibernate` is the default one). While `Spring Data JPA` is the most used option for ORMs and database interactions and that you will rarely need to do raw `Hibernate`, it's good to understand what's happening under the hood. Do not get overwhelmed if you don't understand `Hibernate` well for now, it has a complex learning curve, just do your best.


## Week 19: Building an E-Commerce Website Backend

### **Project Overview**  
In this project, you will build the backend of an **E-Commerce website** using **Spring Boot**. The backend should expose **REST APIs** for managing users, products, orders, and authentication. You will also implement **security features**, including **JWT authentication** and **email verification**, and enhance the system with pagination, filtration, file uploads, input validation, and exception handling.  

### **Objectives**  
- Develop a **RESTful API** for an e-commerce platform.  
- Implement **user authentication and authorization** using **Spring Security & JWT**.  
- Implement **email verification** using **SMTP**.  
- Support **product pagination and filtering**.  
- Enable **file uploads** for product images.  
- Implement **input validation and exception handling**.  
- Write **unit tests** for key functionalities.  
- Use **Spring Data JPA** with **PostgreSQL**.  

### **Entities & Relationships**  
- **User** (Can be a customer or admin)  
- **Product** (Sold by the e-commerce platform)  
- **Category** (Each product belongs to a category)  
- **Order** (Contains multiple products)  
- **OrderItem** (A product inside an order, with quantity and price)  
- **Cart** (Each user has a shopping cart)  

### **Endpoints**  

#### **Authentication & User Management**  
- Register a new user `POST /auth/register`  
- Verify email `GET /auth/verify-email?token={token}`  
- Log in `POST /auth/login`  
- Refresh JWT token `POST /auth/refresh-token`  
- Get the current user's profile `GET /users/me`  
- Update user details `PUT /users/{userId}`  

#### **Product & Category Management**  
- Create a new product `POST /products`  
- Retrieve all products with pagination & filtering `GET /products?page={page}&size={size}&category={category}`  
- Retrieve a product by ID `GET /products/{productId}`  
- Update a product `PUT /products/{productId}`  
- Delete a product `DELETE /products/{productId}`  
- Upload product images `POST /products/{productId}/upload-image`  
- Create a new category `POST /categories`  
- Retrieve all categories `GET /categories`  

#### **Shopping Cart & Order Management**  
- Add a product to cart `POST /cart/{userId}/add/{productId}`  
- View cart items `GET /cart/{userId}`  
- Remove a product from cart `DELETE /cart/{userId}/remove/{productId}`  
- Place an order `POST /orders/{userId}/checkout`  
- Retrieve all orders of a user `GET /orders/{userId}`  
- Retrieve order details `GET /orders/{orderId}`

Bonus: Create a simple front-end that uses your API.


## Week 20: Introduction to NoSQL Databases

Topics:
* Introduction to NoSQL Databases
* MongoDB
* Mongosh & MongoDBCompass
* Spring Data MongoDB
* Collections, Documents, CRUD operations

Resources:

- [Install MongoDB & mongosh on Windows (Amit Thinks)](https://youtu.be/1LiZRYzgM2o?si=isJpU8C-Nk3-NhEE)
- [Complete MongoDB Tutorial (The Net Ninja)](https://youtube.com/playlist?list=PL4cUxeGkcC9h77dJ-QJlwGlZlTd4ecZOA&si=jOhL8DKF3esJIZmL)
- [MongoDB in 1 Hour (Bro Code)](https://youtu.be/c2M-rlkkT5o?si=9taMSnuBpjnLA54H)
- [MongoDB in 30 Minutes (Web Deve Simplified)](https://youtu.be/ofme2o29ngU?si=WsX9BaUFTSDtssP0)
- [Getting Started with Spring Data MongoDB Documentation](https://spring.io/guides/gs/accessing-data-mongodb)
- [Getting started with MongoDB and Spring Boot Documentation](https://www.mongodb.com/en-us/resources/products/compatibilities/spring-boot)
- [MongoDB in Spring Boot Low-Level Tutorial (Telusko)](https://youtu.be/6QnY7Ri_ORw?si=nz5H9eT1YB97WyIC)
- [MongoDB in Spring Boot Tutorial (Amigoscode) (26:23~)](https://youtu.be/ssj0CGxv60k?si=Oy2txu2KsYq9nYbY)
- [MongoDB in Spring Boot Tutorial (Programming Techie) (~15:00)](https://youtu.be/GvPhube6Mls?si=Bc6yBEQ8fsZTo2RV)

Task: <br>
1- Build a simple CRUD application of your choice (task manager, profile manager, books manager, etc) with Spring Data MongoDB. <br>
2- Implement pagination and sorting in MongoDB queries. <br>
3- Implement a search feature using MongoDB’s text indexes. <br>

Bonus: Learn about filtering data.

Note: `Spring Data MongoDB` is so close to `Spring Data JPA`, if you are good with `Spring Data JPA`, this week would be easy for you.


## Week 21: Introduction to Asynchronous Programming in Spring Boot

Topics:
* Blocking vs Non-blocking Programming
* Reactive Programming
* Parallelism vs Concurrency
* Threads and Threading
* CompletableFuture in Java
* @Async & @EnableAsync Annotations in Spring Boot

Resources:

- [Creating Asynchronous Methods in Spring Boot Documentation](https://spring.io/guides/gs/async-method)
- [Blocking vs Non-blocking Programming (Zkrallah)](https://medium.com/@muhammad.heshamyt/introduction-to-blocking-vs-non-blocking-programming-e6f7f0c106db)
- [A Theoretical Guide to Java CompletableFuture (Geekific)](https://youtu.be/xpjvY45Hbyg?si=eMMyf4FUU-C54Vk2)
- [Java CompletableFuture (Lemubit)](https://youtube.com/playlist?list=PLL-4P1BOZnWwauNPsQ_Q13hVL1LHvhy30&si=T3LafPPJ8OFrltAV)
- [CompletableFuture in Java Part I (Tech Recipes)](https://youtu.be/2ddCC6R5u0E?si=P6paHAlMTHFbl6UL)
- [CompletableFuture in Java Part II (Tech Recipes)](https://youtu.be/217XaErWYJE?si=Bn914tBDky5RT9iU)
- [@Async & @EnableAsync in Spring Boot (Java Techie) (recommended)](https://youtu.be/R_gejlOXR7g?si=urMDXE-yF5P_mkfw)
- [@Async & @EnableAsync in Spring Boot (Java Techie) (older but good version)](https://youtu.be/3rJBLFA95Io?si=2GMgVtH7BAf4-EqO)
- [CompletableFuture Guide (GeeksforGeeks)](https://www.geeksforgeeks.org/completablefuture-in-java/)
- [Parallelism vs Concurrency (GeeksforGeeks)](https://www.geeksforgeeks.org/difference-between-concurrency-and-parallelism/)
- [CompletableFuture Guide (Baeldung)](https://www.baeldung.com/java-completablefuture)

Task: <br>
1- Create a method that performs a long-running task asynchronously using CompletableFuture. <br>
* Apply what you have learned using `runAsync` and `supplyAsync`.
* Apply what you have learned using `thenAccept`, `thenApply`, and `thenRun`.
* Run multiple CompletableFuture tasks in parallel and combine their results. <br>

2- Implement a Spring Boot service with an @Async annotated method. <br>
3- Redo the above task but this time configure a custom thread pool executor. <br>

Bonus: Learn about Java Virtual Threads (please note that this is an advanced topic, just take a quick look).


## Week 22: Introduction to Spring WebFlux, Spring Data R2DBC, Reactive Programming in Spring Boot

Topics:
* Introduction to Spring WebFlux
* Non-blocking Code in Spring Boot
* Mono & Flux
* Spring WebFlux Annotation-based programming model
* Spring WebFlux Functional programming model
* Introduction to Spring Data R2DBC

Resources:

- [Web on Reactive Stack Documentation](https://docs.spring.io/spring-framework/reference/web-reactive.html)
- [Spring WebFlux Documentation](https://docs.spring.io/spring-framework/reference/web/webflux.html)
- [Spring WebFlux Annotation-based Model Documentation](https://docs.spring.io/spring-framework/reference/web/webflux/controller.html)
- [Spring WebFlux Functional Model Documentation](https://docs.spring.io/spring-framework/reference/web/webflux-functional.html)
- [Spring Data R2DBC Documentation](https://docs.spring.io/spring-data/relational/reference/)
- [What is Spring WebFlux and When to Use It? (Defog)](https://youtu.be/M3jNn3HMeWg?si=aZApNefpQ1IkBglh)
- [Spring WebFlux (Code With Dilip)](https://youtube.com/playlist?list=PLnXn1AViWyL70R5GuXt_nIDZytYBnvBdd&si=29TxOL3ovga0cqeLv)
- [Spring WebFlux (Java Techie)](https://youtube.com/playlist?list=PLVz2XdJiJQxyB4Sy29sAnU3Eqz0pvGCkD&si=YHMNg8ZiFU9I_u5k)
- [Spring Boot WebFlux CRUD Tutorial with R2DBC (Genka)](https://youtu.be/3LxtmlaX3Y0?si=pl0avyME_xwplAsZ)
- [Spring Boot WebFlux CRUD Tutorial with R2DBC (Bouali)](https://youtu.be/EnUsNVHveyU?si=hW1dvD_vxvrH3q8n)
- [Spring WebFlux Guide (Baeldung)](https://www.baeldung.com/spring-webflux)
- [Basic Introduction to Spring WebFlux (GeeksforGeeks)](https://www.geeksforgeeks.org/basic-introduction-to-spring-webflux/)

Task: <br>
1- Create a Spring WebFlux REST API:
* Set up a Spring Boot project with WebFlux.
* Create a simple reactive endpoint that returns a Mono<String> and a Flux<String>.
* Test the API using Postman. <br>

2- Implement a Reactive CRUD API with WebFlux:
* Create a Product entity and a corresponding ProductController.
* Implement CRUD operations using Mono and Flux.
* Use a reactive database (PostgreSQL + R2DBC for example). <br>

3- Spring WebFlux Functional API:
* Implement the same CRUD API using the functional programming model (instead of the annotation-based approach). <br>

4- Create a Spring MVC REST API:
* Recreate the REST API you did in the first task using Spring MVC instead of Spring WebFlux.
* Add logs in both projects.
* Observe the thread names handling each request. <br>

Bonus:
* Learn how to integrate **Spring Security** with WebFlux (`SecurityWebFilterChain`).  
* Explore `WebClient` as a non-blocking alternative to `RestTemplate`.

Note: <br>
* WebFlux is not always better than Spring MVC. It’s optimized for high-concurrency and real-time streaming applications.
* Use Spring WebFlux when you need to handle thousands of concurrent requests with minimal resource usage.
* If your project does not require reactive programming, sticking with Spring MVC might be a better choice.
* Spring WebFlux is a big topic, don't get overwhelmed, learn as much as you can and revisit later.
* Try to map what you've learned so far to WebFlux and explore alternative approaches for future topics to be applicable to Spring WebFlux.

## Week 23: Caching and Introduction to Redis Cache in Spring Boot

Topics:
* What is caching?
* Caching in Spring Boot
* Redis cache
* Spring Data Redis
* @EnableCaching, @Cacheable, @CacheEvict, and @CachePut annotations
* Jedis and RedisTemplate

Resources:

- [Spring Boot Caching Documentation](https://docs.spring.io/spring-boot/reference/io/caching.html#io.caching)
- [Spring Data Redis Documentation](https://docs.spring.io/spring-data/redis/reference/)
- [Spring Redis Documentation](https://docs.spring.io/spring-data/redis/reference/redis.html)
- [Spring Data Reactive Redis Guide Documentation](https://spring.io/guides/gs/spring-data-reactive-redis)
- [Caching Simply Explained (Simply Explained)](https://youtu.be/6FyXURRVmR0?si=1_bIHY6C6BvEgMvF)
- [How Does Caching Work on the Backend (Software Developer Diaries)](https://youtu.be/bP4BeUjNkXc?si=o3cpJj9CqK-c3I3n)
- [Spring Data Redis in Spring Boot (Developer Hut)](https://youtu.be/fZilHxyj39Q?si=XTSHrfqYwP_v3D-w)
- [Redis in Spring Boot Low-Level Tutorial (Java Codeex)](https://youtu.be/IEJJ1tcAZTo?si=IVHsDSH4soXJ6fAc)
- [Spring Data Redis Part I (Java Techie)](https://youtu.be/oRGqCz8OLcM?si=dEt7-yXp_AXhokNy)
- [Spring Data Redis Part II (Java Techie)](https://youtu.be/vpe4aDu5ixI?si=uvoaxjaQ7q3VgJd-)
- [Spring Data Redis (Java Codeex)](https://youtu.be/0a-RlJx09rg?si=KpEW_Ue4tOWk3NWX)
- [Spring Data Redis Tutorial (Baeldung)](https://www.baeldung.com/spring-data-redis-tutorial)
- [Spring Data Redis Tutorial (GeeksforGeeks)](https://www.geeksforgeeks.org/spring-boot-caching-with-redis/)

Task: <br>
1- Install and run a Redis server locally.
2- Integrate Redis into a Spring Boot Application:
* Create a service class with methods that fetch data (e.g., from a database or an external API).
* Annotate methods with @Cacheable to cache their results.
* Use @CacheEvict and @CachePut annotations where appropriate to manage cache entries. <br>

Bonus: Learn about Spring Data Reactive Redis.

Note: I highly recommend reading the final two articles in the resources of this week as well as the guide documentation.


## Week 24: Real-Time Communication with Sockets & Socket.IO, Streaming with WebRTC Basics.

Topics:
* Raw Sockets, WebSocket, and Socket.IO
* Real-time communication
* Introduction to WebRTC
* ZegoCloud SDK
* Socket.io in Spring Boot
* SockJS & STOMP in Spring Boot

Resources:

- [Introduction to Raw Socket Programming and Implementing the Simplest Chat Service (Zkrallah)](https://medium.com/@muhammad.heshamyt/introduction-to-raw-socket-programming-and-implementing-the-simplest-chat-service-java-17a014703f5fv)
- [Socket.io Documentation](https://socket.io/docs/v4/)
- [Socket.io Wiki Documentation](https://github.com/mrniko/netty-socketio/wiki)
- [Using WebSocket to Build an Interactive Web Application Documentation](https://spring.io/guides/gs/messaging-stomp-websocket)
- [WebSockets Tutorial with Socket.IO (FreeCodeCamp.org)](https://youtu.be/CzcfeL7ymbU?si=Se_M5mHET7ythHYl)
- [WebSocket Tutorial with Spring Boot (Bouali)](https://youtu.be/7T-HnTE6v64?si=Wv4QuUHmgUfpp6Y8)
- [How Does WebRTC Work? (heyletscode)](https://youtu.be/SsN4gl_wV_8?si=tmaXywzUXuGS0AUA)
- [WebRTC in 100 Seconds and Beyond (Fireship)](https://youtu.be/WmR9IMUD_CY?si=6MHOQd3pH17g6Euv)
- [Building a Full Video Call App with ZegoCloud (Bouali)](https://youtu.be/k9WSsYA7-yY?si=qr8D_uVmhbNooPPh)
- [WebRTC Crash Course in JavaScipt (Hussein Nasser)](https://www.youtube.com/watch?v=FExZvpVvYxA)
- [Spring Boot Netty Socket.IO Example (medium)](https://medium.com/folksdev/spring-boot-netty-socket-io-example-3f21fcc1147d)
- [Spring Boot - Web Socket (GeeksforGeeks)](https://www.geeksforgeeks.org/spring-boot-web-socket/)
- [WebRTC API (MDN)](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API)
- [Guide to WebRTC (Baeldung)](https://www.baeldung.com/webrtc)
- [Introduction to WebRTC (GeeksforGeeks)](https://www.geeksforgeeks.org/introduction-to-webrtc/)

Task: <br>
1- Implement a Real-Time Chat Application:
* Set up a Spring Boot project.
* Integrate Socket.IO to handle real-time communication.
* Create a simple chat interface where multiple users can send and receive messages instantly.
* Test the application with a basic front-end or using postman to ensure messages are transmitted in real-time. <br>

2- Explore WebRTC Basics:
* Understand the fundamentals of WebRTC and its use cases.
* Set up a basic peer-to-peer connection between two clients using WebRTC.
* Transmit simple data (e.g., text messages) between the peers. <br>

Bonus: Learn a little about message queues.

Note: <br>
* In most chat services, a cloud messaging service is used to initiate the socket connection programmatically when the receiver is inactive at the moment the sender sends a message. We will discuss cloud messaging services in detail later in the `Firebase` week in the advanced level.
* There aren’t many good resources on implementing `WebRTC` in Spring Boot without using `ZegoCloud`, so feel free to use your preferred LLM or external resources to learn this part. If you find any useful implementations, consider contributing them to the roadmap.
* Many open-source WebSocket implementations are available, with `Socket.io` being the most common. However, some companies use alternatives like `Pusher` or `STOMP`. For brevity, this week’s resources focus on `Socket.io`, but it’s good to be aware of other implementations you might encounter in different environments.


## Week 25: Building a Real-Time Chat Application

### **Project Overview**
In this project, you will build a **real-time chat application** using **Spring WebFlux** and **MongoDB**. The application will support **private messaging** between users, **real-time communication** using **WebSockets (Socket.IO)**, and **persistent chat history storage** in MongoDB.

---

### **Objectives**
- Develop a **fully reactive** backend using **Spring WebFlux**.
- Use **MongoDB** as a NoSQL database for **storing users, messages, and conversations**.
- Implement **WebSockets** for **real-time messaging**.
- Implement **user authentication and authorization** using **Spring Security & JWT**.
- Implement **email verification** using **SMTP**.
- Provide **REST APIs** for **user management** and **chat history retrieval**.
- Implement **input validation and exception handling**.
- Write **unit tests** for key functionalities.

---

### **Entities & Relationships**

#### **User (`users` collection)**
- `id`, `username`, `email`, `password`, `profilePicture`, `status (online/offline)`.
- Users can **send and receive messages**.
- **Email verification** required before accessing chat.
- Feel free to add any additional fields.

#### **Message (`messages` collection)**
- `id`, `senderId`, `receiverId`, `content`, `timestamp`.
- Messages are stored **persistently** in MongoDB.
- Feel free to add any additional fields.

#### **Conversation (`conversations` collection)**
- `id`, `participants[]`, `lastMessage`, `lastUpdated`.
- Stores **user chat sessions** for easy retrieval.
- Feel free to add any additional fields.

---

### **Endpoints**

#### **User Management**
- **Register a new user** → `POST /users/register`
- **Verify email** → `GET /users/verify?token={token}`
- **Login a user** → `POST /users/login`
- **Update user profile** → `PUT /users/{userId}`
- **Get user details** → `GET /users/{userId}`
- Add any missing endpoints.

#### **Chat Management (REST APIs)**
- **Retrieve chat history with a user** → `GET /chats/{userId}`
- **Delete a conversation** → `DELETE /chats/{userId}`
- Add any missing endpoints.

#### **Real-Time Chat (WebSockets - Socket.IO)**
- **Connect to the chat** → `WS /chat/connect` (JWT authentication required)
- **Send a message** → `WS /chat/send`
- **Receive a message** → `WS /chat/receive`
- **Typing indicator** → `WS /chat/typing`
- **Mark message as read** → `WS /chat/status`
- Add any missing endpoints.


---

# Level 3: Advanced (Weeks 26–35)

Focus: Scaling, microservices, Docker, deployment, and advanced concepts.


---
