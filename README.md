# NodeJS_TODO_App

This is a simple TODO app built with Node.js and Express framework. It allows you to create, read, update and delete TODO items. The app also includes user authentication with registration, login and logout functionality, using JSON Web Tokens (JWT) for authentication.

## Technologies Used
* Node.js
* Express.js
* MongoDB
* Mongoose

## Features
* Users can create, update, and delete Todos
* Todos can be marked as completed or incomplete

## API
The app provides a RESTful API to perform CRUD operations on TODO items.
<!-- The API endpoints are:
* GET /todos - Returns a list of all TODO items.
* GET /todos/:id - Returns a single TODO item with the specified ID.
* POST /todos - Adds a new TODO item.
* PUT /todos/:id - Updates an existing TODO item with the specified ID.
* DELETE /todos/:id - Deletes an existing TODO item with the specified ID.
The app uses MongoDB to store the TODO items. The database connection details can be configured in the .env file. >
