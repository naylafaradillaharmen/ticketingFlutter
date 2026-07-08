<div align="center">

# Ticketing App — Mobile Application

> A cross-platform mobile application built with Flutter, providing a seamless ticket purchasing experience through secure authentication, product browsing, and REST API integration.

</div>

---

## Overview

Ticketing App is a Flutter-based mobile application developed to provide users with a simple and intuitive ticket purchasing experience. The application communicates with a Laravel backend through RESTful APIs, allowing users to browse available tickets, manage their accounts, place orders, and manage favorite items.

Built using the BLoC state management pattern, the application focuses on maintainable architecture, responsive performance, and a clean user experience.

This project was developed as an academic project using Flutter and Laravel.

---

## Features

### User Authentication

* User Registration
* Secure Login & Logout
* Session Management

### Ticket Browsing

* Browse Available Tickets
* Category Filtering
* Ticket Details
* Search Functionality

### User Features

* Favorite (Like) System
* User Profile
* Profile Image Upload
* Purchase History

### Ordering

* Ticket Ordering
* Checkout Flow
* Order Confirmation

---

## Tech Stack

### Mobile

* Flutter
* Dart

### State Management

* BLoC
* Repository Pattern
* Remote Data Source

### Networking

* REST API
* Dio
* HTTP

### Local Storage

* Shared Preferences

### Backend

* Laravel REST API

---

## Application Architecture

The application follows a layered architecture to separate presentation, business logic, and data access, making the codebase easier to maintain and scale.

```text
Presentation (UI)
        │
      BLoC
        │
Repository
        │
Remote Data Source
        │
REST API
        │
Laravel Backend
```

---

## Project Structure

```text
lib/
├── core/
├── data/
│   ├── datasource/
│   ├── models/
│   └── repository/
├── presentation/
│   ├── pages/
│   ├── widgets/
│   └── bloc/
└── main.dart
```

---

## Backend Repository

The Laravel backend for this project is available here:

**Ticketing App Backend**

https://github.com/naylafaradillaharmen/ticketingLaravel

---

## My Responsibilities

My contributions to this project included:

* Developing the mobile application using Flutter.
* Implementing BLoC for application state management.
* Applying Repository Pattern and Remote Data Source architecture.
* Integrating Flutter with Laravel REST APIs.
* Building authentication and session management.
* Developing ticket browsing and ordering features.
* Implementing profile management, including image upload.
* Connecting business logic with responsive user interfaces.
* Testing, debugging, and improving application performance throughout development.

---

## Challenges

One of the main challenges during development was maintaining efficient communication between the Flutter application and the Laravel backend while ensuring a responsive and consistent user experience.

Implementing BLoC architecture, handling asynchronous API requests, managing application state, and integrating image uploads were valuable experiences that strengthened my understanding of Flutter application development.

---

## Running the Project

### Prerequisites

* Flutter SDK
* Dart SDK
* Android Studio or Visual Studio Code
* Running Laravel Backend

### Setup

Install Flutter dependencies.

```bash
flutter pub get
```

Update the backend API URL inside the project configuration.

Run the application.

```bash
flutter run
```

---

## Future Improvements

Potential future enhancements include:

* Push notification support.
* Online payment integration.
* QR code-based digital tickets.
* Dark mode.
* Offline data caching.
* Multi-language support.

---

## Project Status

Academic Project

Developed as a cross-platform mobile application demonstrating Flutter development, BLoC state management, REST API integration, and Laravel backend communication.
