# AR App

### Technologies Used

- React Native
- Expo
- SQLite (via `expo-sqlite`)
- React Navigation

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

### Sample
<img src='./assets/Home.jpeg' width="200" height="500">
