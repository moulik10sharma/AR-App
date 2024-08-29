# Login and Registration App

This is a simplified Login and Registration application built with React Native, Expo, and SQLite. The app includes functionality for user authentication and navigation between screens.

## Author: Khaoula's DEV Tutos
## Date: 22 July 2024

## Description:

### Features

- User registration with unique username
- User login with password validation
- Navigation between Login, Registration, and Home screens
- Secure storage of user credentials using SQLite

### Technologies Used

- React Native
- Expo
- SQLite (via `expo-sqlite`)
- React Navigation

### Setup and Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/khaoulasdevtutos/login.git  
    cd login
    ```

2. **Install dependencies:**

    Make sure you have `npx` installed. Then, install the project dependencies:

    ```sh
    npx expo install
    ```

3. **Run the app:**

    Start the Expo development server:

    ```sh
    npx expo start
    ```

    You can then open the app in an emulator or on a physical device using the Expo Go app.

### Components and Screens

- **LoginScreen:** Allows users to log in by entering their username and password.
- **RegisterScreen:** Allows users to create a new account with a unique username and password.
- **HomeScreen:** Displays a welcome message and allows users to log out.

### Database Initialization

- The SQLite database is initialized with a table for storing user credentials (username and password).

### Code Overview

- **App.js:** Main entry point of the application, sets up the SQLiteProvider and NavigationContainer.
- **LoginScreen.js:** Handles user login logic and navigation to the Register screen.
- **RegisterScreen.js:** Handles user registration logic and navigation to the Login screen.
- **HomeScreen.js:** Displays the welcome message and handles user logout.

### Notes

- Ensure you have the Expo CLI installed and configured on your machine.
- This project demonstrates basic user authentication and navigation using React Native, Expo, and SQLite.