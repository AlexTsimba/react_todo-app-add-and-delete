# Todo App

## Overview
This is a study project that is a **Todo application** that allows users to **create**, **read**, **update**, and **delete** todos.

The project is deployed using **gh-pages** and can be viewed [here](https://alextsimba.github.io/Todo_app/#/).

## Technical Stack
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Bulma](https://img.shields.io/badge/bulma-00D0B1?style=for-the-badge&logo=bulma&logoColor=white)

## Features
- **User login and authentication**: The project uses a mock API to handle user authentication and session management. The user is able to register or login and the application will use the information to make authorized requests to the server.
- **Todo CRUD operations**: The user can create, read, update and delete todos.
- **Filtering todos by completion status**: The user can filter the todos that are displayed by their completion status.
- **Error handling and notifications**: The application handles errors that occur during the communication with the server and displays appropriate error messages to the user.

## API
The project uses a **mock API** for data management, The API functions are located in the ./api/todos file. The API uses **REST principles** to handle the CRUD operations on the todos.

## Components
The project is divided into different **components** that are located in the ./components folder:

- **AuthContext**: Provides the authenticated user information to the other components using the context API.
- **AuthProvider**: Wraps the other components and handle the user authentication and session management.
- **AuthForm**: A form that allows the user to login or register.
- **TodoList**: Displays the todos that match the current filter.
- **Header**: Handles the creation of new todos and the toggle of all todos completion status.
- **Filter**: Allows the user to filter the todos by completion status.
- **ErrorNotification**: Displays error messages when something goes wrong.

## Running the project
1. Clone the repository.
2. Run **yarn** to install the dependencies.
3. Run **yarn start** to start the development server.
4. Open **http://localhost:3000** to view the application in the browser.

## Contribution
This project is open for contributions, feel free to submit a pull request with any bug fixes or new features. As a junior react developer, you could help improve the overall functionality and user experience of the Todo App. It's also a great way to gain experience working on a real-world project and collaborating with other developers. We welcome any suggestions and improvements that can be made to this project.
