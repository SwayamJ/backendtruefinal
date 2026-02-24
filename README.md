# backendtruefinal# Ticket Management System API

A Node.js/Express REST API for managing support tickets with role-based access control, JWT authentication, and real-time comments.

## Features

- **User Authentication**: JWT-based authentication with httpOnly cookies
- **Role-Based Access Control**: MANAGER, SUPPORT, and USER roles with different permissions
- **Ticket Management**: Create, view, assign, and update ticket status
- **Comments System**: Add comments to tickets with authorization checks
- **Auto-Increment IDs**: Numeric auto-incrementing IDs for all collections
- **Security**: Password hashing with bcryptjs, secure cookie handling

## Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: JWT (jsonwebtoken)
- **Security**: bcryptjs for password hashing, cookie-parser for cookie management
- **Auto-Increment**: @typegoose/auto-increment plugin

## Installation

1. Clone the repository
```bash
git clone <your-repo-url>
cd backendExmTrue
