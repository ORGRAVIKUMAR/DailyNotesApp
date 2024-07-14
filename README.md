# Notes Pro - Your Digital Notebook

Welcome to the Notes Pro repository! This Android app allows users to create, manage, and organize their notes using Firebase as the backend. Below, we provide an overview of key files, functionalities, and usage instructions:

## Features

- **User Authentication:** Secure user login and registration using Firebase Authentication.
- **Real-time Note Management:** Create, edit, and delete notes, with changes reflected in real-time.
- **Sorting Notes:** Display notes in descending order of their creation timestamp.
- **Logout:** Log out securely with a single click using the menu button.
- **Intuitive UI:** A clean and user-friendly interface for seamless note management.

## Files and Activities

- `CreateAccountActivity.java`: Handles user registration with Firebase Authentication.
- `LoginActivity.java`: Manages user login using Firebase Authentication.
- `MainActivity.java`: The app's main screen for viewing and managing notes.
- `Note.java`: Represents the structure of a note.
- `NoteAdapter.java`: RecyclerView adapter for displaying notes in the main activity.
- `NoteDetailsActivity.java`: Allows users to view and edit note details.
- `SplashActivity.java`: Displays a splash screen on app startup.
- `Utility.java`: Contains utility functions for interacting with Firebase.

## Getting Started

1. Clone or download the repository to your local machine.
2. Set up your Firebase project and add the `google-services.json` file.
3. Open the project in Android Studio.
4. Run the app on your Android device or emulator.
5. Register or log in to start managing your notes!
