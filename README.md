# Local Wi-Fi File Sharing System

A backend application built with Spring Boot that allows users to securely upload, manage, and share files over a local Wi-Fi network. The project is inspired by services like **Send Anywhere** and is developed to explore backend development, authentication, file management, REST APIs, and local network communication.

The application is backend-only and can be tested using **Postman**. Devices connected to the same Wi-Fi network can access the backend using the host computer's local IP address.

## Tech Stack

* Java 17
* Spring Boot
* Spring Security
* JWT Authentication
* Spring Data JPA (Hibernate)
* Microsoft SQL Server
* Maven
* Postman

## Features

* User registration and login
* JWT-based authentication
* Secure file upload and download
* File management
* Temporary share links
* Share codes for file sharing
* QR code generation for file sharing
* One active share link per file
* Link expiration
* Download count tracking
* Local Wi-Fi network access

## Local Network Sharing

The application can be accessed by other devices connected to the **same Wi-Fi network**.

The Spring Boot server runs on the host computer and listens on port `9090`.

For example, if the host computer has the local IP:

```text
192.168.1.100

## Roadmap

* [x] Project setup
* [x] User module
* [x] User registration
* [x] User login
* [x] JWT Authentication
* [x] Spring Security integration
* [x] File upload
* [x] File download
* [x] File listing
* [x] File management
* [x] Temporary share links
* [x] Share codes
* [x] Share tokens
* [x] QR code generation
* [x] Link expiration
* [x] Download count tracking
* [x] Local Wi-Fi network sharing
* [x] Access backend using local IP
* [x] Test APIs over Wi-Fi
* [x] Test file sharing between devices
