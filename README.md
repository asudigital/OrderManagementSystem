Order Management - Online Grocery
Problem Statement
Develop a RESTful API service using Spring Boot to manage an online grocery ordering system for customers, grocery items, and orders. The system should support CRUD operations for each entity, focusing on basic data management without complex business logic.
Requirements
This is a simplified online grocery system aimed at maintaining records of customers, grocery items, and orders.
●	Entities:
○	Customer: Stores customer information.
○	Grocery Item: Represents the available grocery items.
○	Order: Tracks orders placed by customers for grocery items.
●	Relationships:
○	A customer can place multiple orders.
○	An order can contain one or more grocery items.
○	A grocery item can be part of multiple orders.
CRUD Operations
●	Customer Management:
○	Fields: Name, Email, Address, Phone
○	Perform CRUD operations to manage customer information.
●	Grocery Item Management:
○	Fields: Name, Category, Price, Quantity
○	CRUD operations to manage grocery items.
●	Order Management:
○	Fields: Customer, Grocery Item(s), Order Date, Total Price
○	CRUD operations to manage order details.
Endpoints
●	Design RESTful endpoints based on the requirements

Additional Requirements
●	Handle common errors and return appropriate HTTP codes (e.g., 404, entity not found).
●	Unit tests for essential operations. (Optional).
What to Submit?
●	You will be submitting your GitHub code repository for this assignment.
●	Note: An activity will be part of your program to collect this submission.
Additional Resources
●	Local Environment Setup - Backend - For setting up your local environment
●	Setting Up Applications Using Spring Initializr - To learn about generating boilerplate code with Spring Initializr, adding dependencies, integrating databases, and Spring Boot best practices
●	Template for Backend Takehomes
●	What is a Foreign Key Constraint? Understanding Primary & Foreign Keys
●	Spring Boot Global Exception Handler | by Ahmet Emre DEMİRŞEN | Medium
●	Make sure to initialize a new repository for every project on GitHub. Use one of the below for the necessary steps:
○	Installing Git and Creating a Repository  OR 
○	How to Add a New Project to GitHub Repository with Visual Studio Code
●	Postman Collections - Getting Started and Postman Collections - Learning More
●	Basic writing and formatting syntax for README.MD and Markdown Cheatsheet
●	If you are new to building Spring Boot Applications using Spring Data JPA and MySQL, you can take a look at this project: Spring Boot Project | Banking Application using Spring Boot 3, Spring Data JPA (Hibernate), & MySQL

