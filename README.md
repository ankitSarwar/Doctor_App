<h1 align="center"> Doctor_App </h1>

-   This is a Spring Boot application for managing a Doctor and patient Appointment and . It allows users to sign up, sign in, book and view appointment. The application has different levels of access based on user roles: admin, normal user.

> ### [](https://github.com/Rushi-29/REstaurantManageamentSystem#prerequisites)[](https://github.com/Rushi-29/E-commerce#prerequisites)Prerequisites

-   [![MySql](https://camo.githubusercontent.com/ba7cdc426003905af438f0938e0890b3437e590d2c249d671115d19ca32b5df6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f44424d532d4d5953514c253230352e372532306f722532304869676865722d726564)](https://camo.githubusercontent.com/ba7cdc426003905af438f0938e0890b3437e590d2c249d671115d19ca32b5df6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f44424d532d4d5953514c253230352e372532306f722532304869676865722d726564)

-   [![SpringBoot](https://camo.githubusercontent.com/a6677a4ec12bd03f835c62db09a8db96a6d726afe3985c8fbf5c43db9b6cb8ad/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4672616d65776f726b2d537072696e67426f6f742d677265656e)](https://camo.githubusercontent.com/a6677a4ec12bd03f835c62db09a8db96a6d726afe3985c8fbf5c43db9b6cb8ad/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4672616d65776f726b2d537072696e67426f6f742d677265656e)

-   [![Java](https://camo.githubusercontent.com/be815b7d90eac640a950b5ef6e2bd93f30cab6ac1cd9ace277bc560e3e6fc11c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c616e67756167652d4a617661253230382532306f722532306869676865722d79656c6c6f77)](https://camo.githubusercontent.com/be815b7d90eac640a950b5ef6e2bd93f30cab6ac1cd9ace277bc560e3e6fc11c/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c616e67756167652d4a617661253230382532306f722532306869676865722d79656c6c6f77)

> [](https://github.com/Rushi-29/REstaurantManageamentSystem#data-flow)[](https://github.com/Rushi-29/E-commerce#data-flow)Data flow
> ----------------------------------------------------------------------------------------------------------------------------------

In this project, we have four layers-

-   Controller - The controller layer handles the HTTP requests, translates the JSON parameter to object, and authenticates the request and transfer it to the business (service) layer. In short, it consists of views i.e., frontend part.
-   Service -The business layer handles all the business logic. It consists of service classes and uses services provided by data access layers.
-   Repository - This layer mainatains the mySQl-database thing on which CRUD operations are performed
-   Model - This layer consists basically the class level things- the various classes required for the project and these classes consists the attributes to be stored.

> [](https://github.com/Rushi-29/REstaurantManageamentSystem#models)[](https://github.com/Rushi-29/E-commerce#models)Models
> -------------------------------------------------------------------------------------------------------------------------

[](https://github.com/Rushi-29/REstaurantManageamentSystem#features)Features
----------------------------------------------------------------------------

-   User Management:
    -   Sign up:Users can sign up using email
    -   Sign in: Users can sign in with their username and password.
    -   Role-based Access: Admin users have additional privileges, such as viewing all users, while normal users have restricted access.
-  Appointment Management:
    -   book Appointment: Patient can book appoinment by providing time and other details.
-  Doctor Management:
    -   See Appointment: Doctor can see their upcoming Appointments.

> [](https://github.com/Rushi-29/REstaurantManageamentSystem#project-summary)[](https://github.com/Rushi-29/E-commerce#project-summary)Project Summary
> ----------------------------------------------------------------------------------------------------------------------------------------------------
The Doctor App is a basic Spring Boot project designed to facilitate the management of doctor appointments. It provides a simple and user-friendly interface for users to schedule appointments with doctors. The application leverages the Spring Boot framework, which simplifies the development process and enhances efficiency. The Doctor App aims to streamline the appointment booking process and improve overall healthcare service delivery.
