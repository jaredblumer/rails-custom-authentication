# Custom Authentication in Ruby on Rails

This project demonstrates how to implement custom authentication in a Ruby on Rails application, following best practices before integrating a gem like Devise.

## Overview

The project is a simple Ruby on Rails application with user authentication built from scratch. This approach allows developers to understand the fundamentals of authentication, including password encryption, session management, and user login/logout functionality, without relying on third-party libraries.

## Features

- User Signup: Allows users to create an account by providing a username, email, and password.
- User Login: Authenticates users by verifying their credentials and starting a session.
- User Logout: Ends the user session, logging them out of the application.
- Password Encryption: User passwords are securely stored in the database using bcrypt.
- Session Management: The application uses Rails' built-in session management to handle user sessions.
- Basic Access Control: Ensures that only authenticated users can access certain parts of the application.
