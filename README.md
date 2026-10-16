# Event Management System

A full-stack web application for managing academic or community events. This project allows users to browse events, register for them, and view their registrations, while admins can manage events, attendees, and users.

## Project Overview
This project was built to demonstrate practical web development skills using the Node.js ecosystem. It includes authentication, database integration, role-based access, and a clean MVC-style structure.

## Features
- User registration and login
- Secure password hashing using bcrypt
- Session-based authentication
- Event listing with search and date filtering
- Event registration for users
- Prevent duplicate registration for the same event
- Admin dashboard for managing events and users
- Admin panel to view event registrations
- Role-based access for students and administrators

## Tech Stack
- Node.js
- Express.js
- MySQL+
- EJS (templating engine)
- bcryptjs
- express-session
- connect-flash
- MVC architecture

## Project Structure
- `controllers/` - Handles business logic
- `models/` - Database interaction layer
- `routes/` - Application routes
- `views/` - EJS templates for UI
- `public/` - Static assets like CSS and images
- `config/` - Database configuration

## Installation
1. Install dependencies:
   ```bash
   npm install
   ```
2. Create a MySQL database and import the SQL file:
   ```bash
   mysql -u your_username -p < database.sql
   ```
3. Create a `.env` file in the project root with the following variables:
   ```env
   DB_HOST=localhost
   DB_USER=your_username
   DB_PASSWORD=your_password
   DB_NAME=event_management
   SESSION_SECRET=your_secret_key
   ```
4. Start the application:
   ```bash
   npm start
   ```
5. Open the app in your browser at:
   ```bash
   http://localhost:3000
   ```

## Resume-Friendly Description
This project demonstrates end-to-end development of a web application from backend logic to database interaction and UI rendering.

## Technical Skills Achieved
- Built a full-stack web application using Node.js and Express.js
- Implemented secure authentication and authorization
- Worked with MySQL databases and SQL queries
- Applied CRUD operations for events, users, and registrations
- Used middleware for sessions, flash messages, and request handling
- Structured the application using MVC architecture
- Created dynamic web pages using EJS templates
- Implemented password hashing and protected routes

## What to Mention in Your Resume
You can describe this project as:

- Developed an Event Management System using Node.js, Express.js, MySQL, and EJS
- Built user authentication, event registration, and admin management features
- Implemented secure login with password hashing and session management
- Designed and connected a relational database for users, events, and registrations
- Created a role-based admin panel for managing events and users

## Example Resume Bullet Points
- Developed a complete event management web application using Node.js, Express.js, MySQL, and EJS.
- Implemented secure user registration/login, session management, and password hashing with bcrypt.
- Designed database relationships for users, events, and registrations to support real-world functionality.
- Built admin features for creating, editing, deleting, and tracking event registrations.
- Applied MVC architecture and middleware-based request handling to create a maintainable web app.
# event_management
