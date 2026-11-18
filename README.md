# Web Assignment

## Project Overview
This project is a backend web application developed using Node.js, Express.js, and MongoDB.

It demonstrates the implementation of RESTful APIs and CRUD (Create, Read, Update, Delete) operations for managing user data.

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- JavaScript
- bcrypt

## Project Structure

```text
backend-assignment/
│
├── backend/
│   └── src/
│       ├── config/
│       │   └── db.js
│       ├── models/
│       │   └── user.model.js
│       ├── routes/
│       │   └── user.routes.js
│       └── index.js
│
├── .env.example
├── .gitignore
├── package.json
└── README.md
```

## Features
- User registration
- User login
- Password hashing using bcrypt
- MongoDB database connectivity
- REST API development
- CRUD operations for user management

## Installation and Setup

1. Clone or download the repository.
2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file and configure your environment variables:

```env
PORT=8000
MONGO_URI=your_mongodb_connection_string
```

4. Start the development server:

```bash
npm run dev
```

## API Endpoints

The application provides endpoints for user-related operations, including registration, login, retrieving users, updating user details, and deleting users.

## Learning Outcomes

- Understanding backend development with Node.js.
- Working with Express.js and REST APIs.
- Connecting applications to MongoDB.
- Implementing authentication and password hashing.
- Understanding CRUD operations.

## Author

Yashika Choudhary

B.Tech Computer Science and Engineering
