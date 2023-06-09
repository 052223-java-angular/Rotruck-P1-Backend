# P1 - Individual Programming Project

## Introduction

This is full-stack web development project that will utilize a third party api as well as being able to handle requests
on the backend like an API. This application will be a kanban style task board. You will be able to add tasks, edit tasks, move tasks between the different categories, and delete tasks. The taskboard will give daily inspirational quotes utilizing a 3rd part api.

## User Stories

- **As a user**, I want to be able to register a new account
- **As a user**, I want to be able to log in and keep my board to myself.
- **As a user**, I want to to be able to create a todo list and keep track of the workflow
- **As a user**, I want to add new tasks to the to do list.
- **As a user**, I want to edit tasks when needed.
- **As a user**, I want to to be able to delete tasks.
- **As a user**, I want to be able to move items from one status to another.
- **As a user**, I want to be able to delete all items from the board.
- **As a user**, I want to be able to have my tasks persist over time while still on the board.
- **As a user**, I want to to be able to have a daily inspirational quote.

## MVP (Minimum Viable Product)

- User registration and login
- Browsing and searching for task
- Add a new task
- Modify tasks
- Delete a task
- Delete all tasks
- Be able to drag items from one status to another

## Stretch Goals

- Be able to create multiple boards that you can move between.
- Be able to edit the frequency of dad jokes

## Tech Stacks

- **Angular**: Used in the front end for styling.
- **HTML**: Used in the front end development of the page.
- **CSS**: Used to style the page.
- **REST API**: 3rd party api used to obtain the dad joke.
- **Typescript**: The main programming language used for building the application.
- **PostgreSQL**: Used as the database to store user, product, and order data.
- **Maven or Gradle**: Used for managing project dependencies.
- **JUnit**: A testing framework for Java applications, used to ensure our code works as expected.
- **JDBC (Java Database Connectivity)**: An API for connecting and executing queries on the database.
- **BCrypt**: A Java library for hashing and checking passwords for security.
- **JUnit, Mockito, and PowerMock**: Used for unit and integration testing.
- **Git and GitHub**: Used for version control.

## Requirements

- **Clean Codebase**: All code should be clean and well-documented. The repository should not include any unnecessary files or folders such as the `target/`, `.DS_Store`, etc. All files and directories should be appropriately named and organized.

- **Database Design**: The database should be designed following the principles of the 3rd Normal Form (3NF) to ensure data integrity and efficiency. An Entity Relationship Diagram (ERD) should be included in the documentation.

- **Secure**: All sensitive user data such as passwords must be securely hashed before storing it in the database. The application should not display any sensitive information in error messages.

- **Error Handling**: The application should handle potential errors gracefully and provide clear and helpful error messages to the users.

- **Testing**: The application should have a high test coverage. Unit tests and integration tests should be implemented using JUnit, Mockito, and PowerMock.

- **Version Control**: The application should be developed using a version control system, preferably Git, with regular commits denoting progress.

- **Documentation**: The repository should include a README file with clear instructions on how to run the application. Code should be well-commented to allow for easy understanding and maintenance.

- **Scalable**: The design of the application should be scalable, allowing for easy addition of new features or modifications in the future.
