# RBAC Dashboard

RBAC Dashboard is a full-stack MERN application that offers robust **Role-Based Access Control** with secure authentication and intuitive user management. Admins can register users, assign roles, and manage permissions seamlessly. With dynamic role assignment and a responsive UI, it’s designed to streamline access control for enterprise-grade applications.

**Live Website**: [RBAC Dashboard](https://kshitij-rbac.onrender.com/)

---

## Features

### Frontend

- **User Registration**: Register users securely via form validation and backend integration.
- **Authentication**: Secure login and logout functionality with session persistence.
- **Role-Based Access Control**: Separate interfaces and access restrictions for Admin and User roles.
- **Admin Dashboard**:
  - View all registered users.
  - Promote users to admin or demote them.
  - Delete users from the system.
- **Responsive UI**: Built with Bootstrap to ensure usability across all devices.
- **Alerts & Notifications**: Feedback for successful actions and error handling.

### Backend

- **User Model & Authentication**: Uses JWT and bcrypt for secure token-based login.
- **Role Management**: Dynamically assign and verify roles for access control.
- **Protected Routes**: Middleware checks for authorized roles before granting access.
- **RESTful APIs**: Well-structured endpoints for all user and role operations.
- **MongoDB Integration**: Stores users securely and efficiently using Mongoose.

---

## Tech Stack

### Frontend

- **React.js**: UI framework for component-based development.
- **Bootstrap**: For responsive and modern styling.
- **Axios**: For making API requests.

### Backend

- **Node.js**: JavaScript runtime for server-side operations.
- **Express.js**: Framework for building RESTful APIs.
- **MongoDB**: NoSQL database for storing users and roles.
- **Mongoose**: ODM for MongoDB integration.
- **JWT & Bcrypt**: For authentication and password security.

---

## Installation & Setup

### 1. Prerequisites

- **Node.js** (v14 or later)
- **MongoDB** (Local or Atlas)

### 2. Clone the repository

```bash
git clone https://github.com/krish3742/RBAC-Dashboard.git
```

### 3. Backend Setup

1. Go to the backend folder:

   ```bash
   cd .\Backend\
   ```

2. Follow the instructions in the `README.md` file inside the `backend` folder for further setup.

### 4. Frontend Setup

1. Go to the frontend folder:

   ```bash
   cd .\rbac_frontend\
   ```

2. Follow the instructions in the `README.md` file inside the `frontend` folder for further setup.

---

## License

This project is licensed under the **MIT License**.

---

## Contact

- **Author**: Kshitij Agrawal
- **Email**: akshitij70@gmail.com
- **GitHub**: [@krish3742](https://github.com/krish3742)
