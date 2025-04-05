# RBAC Dashboard Backend

This is the backend for the **RBAC Dashboard** application, built with **Node.js**, **Express**, and **MongoDB**. It provides secure APIs for user authentication, role management, and access control.

## Features

- **User Registration and Login**: Secure authentication using JWT and hashed passwords.
- **Role-Based Access Control**: Middleware to restrict access based on roles (Admin/User).
- **Admin Actions**:
  - View all users
  - Promote/demote users
  - Delete users
- **Error Handling**: Proper error responses for all API failures.

## Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Authentication**: JWT, bcrypt

## Installation

1. Install dependencies:

   ```bash
   npm install
   ```

2. Set up environment variables:

   Create a `nodemon.json` file in the `backend/` directory and configure the following:

   ```env
   "PORT": 3002,
    "CONNECTION_STRING": MongoDB_Connection_String,
    "SECRET_KEY": KEY,
    "CORS_ORIGIN_URL": Frontend_URL
   ```

3. Start the server:

   ```bash
   npm start
   ```

The server will run at `http://localhost:3002`

## License

This project is open-source and available under the [MIT License](LICENSE).
