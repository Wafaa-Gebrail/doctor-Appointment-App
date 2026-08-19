# 🩺 Doctor Appointment App

A Flutter app that allows patients to browse doctors, view profiles, and book appointments easily. It focuses on clean architecture and maintainable code.

## Clean Code Principles

- Clear separation of layers
- Follows SOLID principles
- Modular, testable, and scalable
- Organized and reusable widgets/components

## Flutter Flavors for CI/CD

The app uses **Flutter Flavors** to manage multiple environments:

- `dev` – for local development
- `prod` – for production release

This setup makes CI/CD smoother and helps with easier environment configuration (API base URLs, app names/icons, etc.).

## State Management

This app uses the **BLoC (Business Logic Component)** pattern for state management.

- Ensures separation between UI and business logic
- Makes the app more testable and maintainable
- Helps manage complex states in a clean and scalable way
