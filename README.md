# Noy Horen Project  


## Business Cards API with User Login System
### Overview

This project is a Node.js Express application that provides a user login system along with a RESTful API for managing business cards. Each card represents a business and includes "like" functionality. The project includes all CRUD (Create, Read, Update, Delete) operations for managing the cards.

## Features

### 1.User Management
   - Registration: Users can register by providing necessary details, which are validated and stored securely in the database.
   - Authentication: Secure user authentication using JWT (JSON Web Tokens).
   - Password Hashing: Passwords are hashed using bcrypt to ensure security.
   - User Profile: Fetch and update user profile information.

### 2.Card Management
   - Create Cards: Users can create new cards with specific attributes.
   - Read Cards: Fetch a list of all cards or details of a specific card.
   - Update Cards: Update information on existing cards.
   - Delete Cards: Remove cards from the database.

### 3.Database Integration
   - MongoDB: Data is stored in a MongoDB database using Mongoose for schema definitions and queries.

### 4.Middleware and Utilities
   - CORS: Enabled cross-origin resource sharing using the `cors` package.
   - Logging: HTTP request logging using `morgan` for easier debugging and monitoring.
   - Environment Variables: Configuration management using `dotenv`.

### 5.Validation and Error Handling
   - Input Validation: Request data validation using Joi to ensure data integrity.
   - Centralized Error Handling: Consistent error responses and error logging.

### 6.Developer Experience
   - Typescript: TypeScript is used for type checking and improved code quality.
   - Chalk and Figlet: Used for enhancing console output and server start messages.

### 7.Additional Tools
   - Underscore: Utility library for data manipulation and functional programming.
   - bcrypt: Secure password hashing.
   - jsonwebtoken: JWT-based authentication.

## Getting Started

1. Install Dependencies: Run `npm i` to install all required dependencies.
2. Set Up Environment Variables: Create a `.env` file based on the provided `.env.example` and configure your environment variables.
3. Run the Server: Use `npm run dev` to start the server on port 8080.
4. Use the (http://localhost:8080) link for API Documentation.
















