# Link - Java Chat Application

**Course Title:**\
(CSE 1709) Advanced Programming

**Under Supervision:**\
Dr. Hadder

**Team Members:**

- Youssef Ebrahim (Interface of login and signup)
- Mario Saleh (Server)
- Mario Atef (Database)
- Beshoy Nabil (GUI)
- AbdAlraouf AbdAlKareem AlMasri(GUI)

**Project Title:**\
Link - Java Chat Application

---

## Introduction

Welcome to **Link**, a Java-based chat application designed to facilitate real-time communication between users. This project leverages Java’s networking capabilities to create a robust and scalable chat system. It supports **one-on-one chats**, providing a user-friendly interface for seamless interaction.

## Purpose

The purpose of this project is to develop a fully functional chat application using Java. The application aims to offer:

- **User authentication**
- **Real-time messaging**
- **Message persistence**

## Methodology

The project is built using a **client-server architecture**, where:

- The **server** manages user connections, authentication, and message routing.
- The **clients** are built using **JavaFX** for the user interface, handling message display and interaction.
- **SQL** is used for storing user credentials and message history.

## Project Overview

Link is a real-time chat application providing a seamless one-on-one messaging experience. The application features:

- **User authentication**
- **Message persistence**
- A **modern user interface** built with JavaFX.

## Requirements

To run the application, you'll need:

- **Java Development Kit (JDK) 8 or higher**
- An Integrated Development Environment (IDE) such as **NetBeans** or **Eclipse**
- **JavaFX** for the user interface
- **XAMPP** for database management (or any other relational database)
- mysql-connector-j-8.4.0.jar for connect with java

## Architecture

Link uses a **client-server architecture** with the following components:

1. **Client Application:** A JavaFX-based user interface.
2. **Server Application:** A Java server that handles client connections, authentication, and message routing.
3. **Database:** Used for storing user credentials and message history.

### User Interface

The user interface is designed with **JavaFX** for a modern, interactive experience. It includes:

- **Login Screen:** For user authentication.
- **Chat Window:** Displays messages and includes an input field for typing new messages.
- **User List:** Shows online users and available chat groups.

### Server-Side Code

The server application is built with **Java's ServerSocket** and **Socket** classes to handle multiple client connections. It manages:

- **User authentication**
- **Message routing**

### Client-Side Code

The client application is built using **JavaFX** for the user interface and communicates with the server using **sockets**. It handles sending and receiving messages between users.

## Conclusion

The Link chat application demonstrates the use of Java for building real-time communication systems. By utilizing a **client-server architecture** and Java's networking capabilities, this project provides a solid foundation for further improvements. Potential future enhancements could include:

- A more advanced user interface
- Additional security features
- Support for multimedia messages
