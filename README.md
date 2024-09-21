# Contact Management


## Overview

**Contact Management** is a backend application built using Node.js and Express to manage contacts efficiently. This app utilizes JSON Web Tokens (JWT) for secure authentication and includes various middlewares for robust API management.

## Features

- **User Authentication:** Secure login and registration using JWT.
- **Contact Management:** Create, read, update, and delete contacts.
- **Middleware Support:** Organized request handling with custom middlewares.
- **RESTful API:** Fully functional API endpoints for seamless integration.

## Technologies Used

- **Node.js**
- **Express.js**
- **MongoDB** (for data storage)
- **JSON Web Token (JWT)** (for authentication)
- **Mongoose** (for MongoDB object modeling)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (Local or Cloud instance)
- A tool for testing APIs (like Postman)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/kirankk1/Contact_management.git
   cd Contact_management
   
2. Install the dependencies:
    ```bash 
    npm install

3. Set up your environment variables:
  Create a .env file in the root directory and add the following:

  env
  PORT=your_port_number
  MONGO_URI=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret
  Start the server:

  ```bash
  npm start
  Your app will be running at http://localhost:your_port_number.
  ```
API Endpoints
Authentication
POST /api/auth/register - Register a new user
POST /api/auth/login - Authenticate user and receive a token
Contacts
GET /api/contacts - Get all contacts (requires authentication)
POST /api/contacts - Create a new contact (requires authentication)
GET /api/contacts/:id - Get a specific contact by ID (requires authentication)
PUT /api/contacts/:id - Update a specific contact (requires authentication)
DELETE /api/contacts/:id - Delete a specific contact (requires authentication)
Usage
Once the server is running, you can use tools like Postman to interact with the API. Make sure to include the JWT token in the headers for protected routes.

Contributing
Contributions are welcome! Please fork the repository and create a pull request for any improvements or bug fixes.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Node.js
Express.js
MongoDB
JSON Web Tokens
Feel free to reach out for any questions or suggestions!

vbnet
 
