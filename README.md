# Login-Backend-API

A simple backend Todo API built with **Node.js**, **Express.js**, **SQLite**, **JWT authentication**, and **bcrypt password hashing**.

## Features
- User registration
- User login
- Password hashing with bcrypt
- JWT-based authentication
- Protected todo routes
- SQLite database integration
- Basic REST API testing with `.rest` file

## Tech Stack
- Node.js
- Express.js
- SQLite
- bcryptjs
- jsonwebtoken

## Project Structure
- `src/server.js` – app entry point
- `src/db.js` – database setup
- `src/routes/authRoutes.js` – register and login routes
- `src/routes/todoRoutes.js` – todo-related routes
- `src/middleware/authmiddleware.js` – JWT auth middleware

## Purpose
This project was built for learning backend development by practicing authentication, route protection, database operations, and API testing in a real project structure.

## Notes
Environment variables such as `JWT_SECRET` are stored in `.env` and are not pushed to GitHub.

