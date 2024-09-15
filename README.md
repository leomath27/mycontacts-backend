# MyContacts Backend API

A complex Node.js backend API for managing contacts with authentication using Express, MongoDB, JWT, and Mongoose.

## Features

User Authentication: Register and login users with hashed passwords and JWT authentication.
Contact Management: Create, update, delete, and retrieve contacts for authenticated users.
Validation: Input validation to ensure all fields are mandatory when creating a contact or registering a user.
Error Handling: Centralized error handling for easier debugging.
JWT Authentication: Routes are protected with JSON Web Tokens for secure access to the API.

## API Endpoints

- **POST** `/api/users/register`: Register user
- **POST** `/api/users/login`: Login user
- **GET** `/api/contacts`: Get all contacts (Protected)
- **POST** `/api/contacts`: Create a contact (Protected)

