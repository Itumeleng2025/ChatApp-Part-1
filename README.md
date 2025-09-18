Chat App (Part 1 – Registration and Login)

This project is a Java Swing-based chat application.
The current phase focuses on registration and login features using Object-Oriented Programming (OOP) principles.

Features

User Registration

Username must contain an underscore and be no more than 5 characters.

Password must be at least 8 characters, contain an uppercase letter, a number, and a special character.

Phone number must follow South African format: +27XXXXXXXXX.

User Login

Authenticates using registered username and password.

Secure constant-time password comparison.

Displays success or error messages in the GUI.

Swing GUI

Interactive forms for registration and login.

Real-time validation feedback.

Encapsulation & Validation

UserCredentials class stores and validates user data immutably.

Exception handling for invalid inputs.

Project Structure
chatapp/
 ├── UserCredentials.java   # Stores and validates user details
 ├── Registration.java      # Handles user registration and input validation
 ├── Login.java             # Handles user authentication
 ├── Main.java              # Entry point for the application
