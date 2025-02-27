# 🌦️ Weather App

![GitHub](https://img.shields.io/github/license/yourusername/weather-app) ![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/weather-app) ![GitHub issues](https://img.shields.io/github/issues/yourusername/weather-app)

A modern, feature-rich **Weather App** built using **Jetpack Compose**, **Clean MVVM Architecture**, and **Modular Design**. This app provides real-time weather updates, multi-day forecasts, location-based weather, and more, all while showcasing best practices in Android development.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [How to Contribute](#how-to-contribute)
- [License](#license)

---

## 🌟 Overview

The **Weather App** is designed as a capstone project to demonstrate advanced Android development skills. It leverages a **multi-module architecture** with feature-based modularization, ensuring scalability, maintainability, and reusability. The app integrates modern tools like **Jetpack Compose** for UI, **Hilt** for dependency injection, and **Retrofit** for networking.

---

## ⚡ Key Features

- **Real-Time Weather Data**: Fetch current weather data for any location.
- **Multi-Day Forecast**: View weather predictions for the upcoming week.
- **Hourly Forecast**: Get hourly weather updates for the current day.
- **Location-Based Weather**: Automatically detect and display weather for the user's current location.
- **Favorites Management**: Save and manage favorite locations.
- **User Preferences**: Customize units (metric/imperial), enable dark mode, and configure notifications.
- **Offline Mode**: Cache weather data for offline access.
- **Push Notifications**: Receive alerts for severe weather conditions.
- **Dynamic Animations**: Weather-specific animations (e.g., rain, sun).
- **Data Visualization**: Display temperature trends using charts.

---

## 💻 Technologies Used

- **Programming Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Architecture**: Clean MVVM with Modular Design
- **Networking**: Retrofit, OkHttp
- **Caching**: Room Database
- **Dependency Injection**: Hilt
- **Notifications**: Firebase Cloud Messaging (FCM)
- **Charts**: MPAndroidChart or Compose Charts
- **Permissions**: Location permissions with runtime handling
- **Testing**: JUnit, Mockito, Espresso, Compose Testing APIs
- **Build System**: Gradle

---

## 📂 Project Structure

The project follows a **modular architecture** with the following modules:

- **`core`**: Shared utilities, extensions, and base classes.
- **`data`**: Networking, caching, and repositories for shared data.
- **`domain`**: Use cases and domain models for business logic.
- **`features`**: Feature-specific modules:
  - **`home`**: Displays current weather and forecasts.
  - **`search`**: Allows users to search for cities.
  - **`favorites`**: Manages saved favorite locations.
  - **`settings`**: Handles user preferences.
- **`app`**: Entry point of the app, combining all modules.

Directory Tree:
#### Figma Design
<img width="390" alt="Home (1)" src="https://github.com/user-attachments/assets/45e13691-890e-4194-8342-982d9be6b851" />
<img width="390" alt="Add" src="https://github.com/user-attachments/assets/631f9aa3-7a40-407a-8c2e-1ece038f0654" />
