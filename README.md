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

```
WeatherApp/
├── app/
├── core/
├── data/
├── domain/
├── features/
│ ├── home/
│ ├── search/
│ ├── favorites/
│ ├── settings/
├── build.gradle
├── settings.gradle
```

## 🛠️ Setup Instructions

### Prerequisites

- Android Studio (latest version recommended)
- JDK 11 or higher
- Git installed on your machine

### Steps to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```
2. **Open in Android Studio**:
  - Open the project in Android Studio by selecting the build.gradle file.
3. **Set Up API Keys**:
  - Obtain an API key from OpenWeatherMap or another weather service.
  - Add the API key to the local.properties file:
  ```bash
  WEATHER_API_KEY=your_api_key_here
  ```
4. **Install Dependencie**:
 - Ensure all dependencies are downloaded by syncing the Gradle files.
5. **Run the App**:
 - Connect a physical device or use an emulator.
 - Click the "Run" button in Android Studio.
# 👥 How to Contribute

We welcome contributions! Here’s how you can get involved:

1. **Fork the Repository**:
   - Fork this repository to your GitHub account.

2. **Create a Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Changes**:
- Implement your changes or fixes.

4. **Test Your Changes**:
- Ensure all tests pass and the app runs smoothly.

5. **Submit a Pull Request**:
- Push your branch and create a pull request with a detailed description of your changes.

---

## Contribution Guidelines

- Follow the **Clean Code** principles.
- Write meaningful commit messages.
- Ensure your code adheres to the project's coding standards.
- Add unit tests for new features or bug fixes.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Thanks to [OpenWeatherMap](https://openweathermap.org/) for providing the weather API.
- Special thanks to the open-source community for their contributions and support.

---

## 📞 Contact

For questions or feedback, feel free to reach out:

- **Email**: aumaidm.m.c@gmail.com  
- **GitHub**: [@aumaidkh](https://github.com/aumaidkh)  
#### Figma Design
<img width="390" alt="Home (1)" src="https://github.com/user-attachments/assets/45e13691-890e-4194-8342-982d9be6b851" />
<img width="390" alt="Add" src="https://github.com/user-attachments/assets/631f9aa3-7a40-407a-8c2e-1ece038f0654" />
