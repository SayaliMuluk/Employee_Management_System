
# Employee Management System




## Overview
The Employee Management System is a web application built with Spring Boot, Bootstrap, and Thymeleaf. It provides a user-friendly interface for managing employee data. Users can view, add, edit, and delete employee information through a browser-based interface.
## Features
View Employees: Display a list of all employees with details such as name, position, and department.

Add Employee: Create new employee records with relevant information.

Edit Employee: Modify existing employee details using an intuitive interface.

Delete Employee: Remove employee records from the system.
## Technologies Used

Spring Boot: Framework for building and running the application.

Bootstrap: Front-end framework for responsive and visually appealing design.

Thymeleaf: Java templating engine for rendering HTML views.
## Prerequisites

Java: Version jdk 22

Maven: Build tool for managing dependencies and building the project

IDE: Spring Tool Suite 4
## Usage

View Employees: Navigate to the "/" endpoint to see a list of all employees.

Add Employee: Use the "/addemp" endpoint to create a new employee record.

Edit Employee: Use the Edit button next to any employee record to modify the employee's details. You will be redirected to the "/edit/{id}" endpoint to make your changes.

Delete Employee: Use the Delete button next to any employee record to remove it from the system. This action will redirect you to the "/delete/{id}" endpoint.
