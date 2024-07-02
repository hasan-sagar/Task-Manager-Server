

# Task Manager - Back-End

## Project Intro
This repository contains the server-side code for a task management application. The server is responsible for handling all the backend operations, including user authentication, task creation, updating, deletion, and data storage. It provides APIs that the client-side application uses to interact with the server.

## Features

-   **User Authentication**: Manages user registration, login, and authentication using JWT (JSON Web Tokens) for secure access.
-   **Task Management**: Allows users to create, read, update status, and delete tasks. Each task can have attributes such as title, description, date, and status.
-   **Data Persistence**: Uses a database (likely MongoDB) to store user and task data persistently.
-   **API Endpoints**: Exposes RESTful API endpoints for client-side applications to perform CRUD (Create, Read, Update, Delete) operations on tasks and manage user sessions.
-   **Middleware**: Implements middleware for handling requests, authentication, and error handling.
-   **Environment Configuration**: Supports configuration via environment variables for different deployment environments..

## Prerequisite
- Nodejs v18+

## Technologies

-   **Frontend Framework**: ExpressJs, JavaScript
-   **Database**: MongoDB
-   **Orm**: Mongoose

### Backend api endpoint : https://task-manager-server-91ot.onrender.com/api/v1
