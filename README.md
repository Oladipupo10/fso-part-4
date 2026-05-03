# fso-part-4 
# Full Stack Open Part 4 – Blog List Backend

This project is the backend for the Blog List application from **Full Stack Open Part 4**.

It is built with **Node.js**, **Express**, and **MongoDB**, and provides a REST API for managing blogs and users.

---

## Features

- Create, read, update, and delete blogs
- User authentication with JSON Web Tokens (JWT)
- Password hashing with bcrypt
- Blog ownership tied to authenticated users
- Unit tests and integration tests with Node test runner / Supertest
- Error handling and middleware support

---

## Technologies Used

- Node.js
- Express
- MongoDB / Mongoose
- bcrypt
- jsonwebtoken
- dotenv
- cors
- supertest
- Node test runner

---

## Installation

Clone the repository and install dependencies:

```bash
npm install
MONGODB_URI=your_production_database_url
TEST_MONGODB_URI=your_test_database_url
SECRET=your_jwt_secret
PORT=3001
development server npm run dev
runnig test npm test
