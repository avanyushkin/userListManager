# User Management App
![React](https://img.shields.io/badge/React-18.2.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Maintained-brightgreen)

A simple CRUD (Create, Read, Update, Delete) application for managing user lists, built with React.

## Features
- Add new users
- View user information
- Edit existing users
- Delete users

## Technologies Used
- React 18
- React Icons (for delete/edit icons)
- Class components with state management
- Local application state

## Technical Implementation
graph TD
    A[App] --> B[Header]
    A --> C[Users]
    A --> D[AddUser]
    C --> E[User]
    E --> D[AddUser-as-Edit-Form]

## TODO
- Include API documentation
- Add performance benchmarks
- Include internationalization details
  
