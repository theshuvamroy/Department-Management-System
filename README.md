# Department Management System

## Overview

A comprehensive web application for managing academic departments, including courses, materials, and user management with different roles (students, lecturers, and admins).

The Department Management System (DMS) is designed to streamline educational operations by providing a platform for course management, student enrollment, learning materials distribution, and administrative tasks. The application features role-based access controls, real-time updates, and a responsive user interface.


## Core Features

- Authentication & Authorization
- User registration and login
- JWT-based authentication
- Role-based access control (Student, Lecturer, Admin)
- Password hashing with bcrypt

## Course Management

- Create, view, update, and delete courses
- Course enrollment for students
- Course assignment for lecturers
- Course details with enrolled students

## Learning Materials

- Upload and manage course materials
- Download materials
- Organize materials by course
- User Management
- User profiles with role information
- Update user details
- View enrolled/teaching courses

## Technology Stack

### Frontend

- Next.js
- TypeScript
- Tailwind CSS
- Axios for API requests
- React Toastify for notifications

### Backend

- Express.js
- TypeScript
- MongoDB with Mongoose
- JWT for authentication
- Multer for file uploads
- CORS for cross-origin requests
