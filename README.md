🔷 Project Title

Flutter Local Storage App (SQLite, Hive, SharedPreferences)

🔷 Project Description

This project is a Flutter-based mobile application developed as part of an Academic Learning Assignment (ALA). The main purpose of this application is to demonstrate the implementation of different local storage techniques in Flutter.

The app allows users to store, retrieve, and update data using three different storage methods: SQLite, Hive, and SharedPreferences. Each method represents a different way of handling local data in mobile applications.

This project helps in understanding how data persistence works in Flutter and how different storage mechanisms are used based on application requirements.

🔷 Features
Store user input data
Retrieve stored data
Update existing data
Demonstration of 3 storage techniques:
SQLite (Relational Database)
Hive (NoSQL Database)
SharedPreferences (Key-Value Storage)
Simple and user-friendly interface
Works offline
🔷 Technologies Used
Flutter (UI Framework)
Dart (Programming Language)
SQLite (Structured storage)
Hive (Lightweight NoSQL database)
SharedPreferences (Key-value storage)
🔷 Project Workflow
User enters data in the input field
User selects a storage method
Data is stored locally on the device
User can retrieve the stored data
Data is displayed on the screen
User can update the stored data
🔷 Storage Techniques Explained
🔹 SQLite

SQLite is a relational database used to store structured data in the form of tables.

Uses SQL queries
Suitable for large datasets
Supports CRUD operations (Create, Read, Update, Delete)

In this project, SQLite is used to store user data in a table format.

🔹 Hive

Hive is a fast and lightweight NoSQL database designed for Flutter applications.

No tables required
Stores data as key-value pairs
Very fast performance
Works offline

In this app, Hive is used to store and retrieve data using simple keys.

🔹 SharedPreferences

SharedPreferences is used to store small amounts of data in key-value pairs.

Simple and easy to use
Suitable for storing settings and preferences
Lightweight

In this project, it is used to store basic user input data.

🔷 Code Explanation (Main Logic)

The application is built using Flutter’s StatefulWidget to manage dynamic data updates.

🔸 Initialization
Hive is initialized at the start of the app
A Hive box is opened for storing data
🔸 SQLite Functions
Database is created using openDatabase()
Table is created using SQL query
Data is inserted and retrieved using database functions
🔸 Hive Functions
Data is stored using box.put()
Data is retrieved using box.get()
🔸 SharedPreferences Functions
Data is stored using setString()
Data is retrieved using getString()
🔸 UI Design
TextField for user input
Buttons for each storage operation
Output section to display stored data
🔷 Folder Structure
lib/
 └── main.dart
🔷 How to Run the Project
Install Flutter SDK
Open the project in Android Studio / VS Code
Run the following commands:
flutter pub get
flutter run
Launch emulator or connect device
🔷 Output
User can input data
Data is stored using selected storage method
Data can be retrieved and displayed
Application runs successfully without errors
🔷 Advantages
Helps understand multiple storage techniques
Easy to use and implement
Works without internet
Good for beginners
🔷 Limitations
UI is basic
Not suitable for large-scale production apps
Limited to text data
🔷 Future Improvements
Add better UI/UX design
Add Firebase cloud storage
Store images and files
Add authentication system
🔷 Conclusion

This project successfully demonstrates the implementation of local storage in Flutter using SQLite, Hive, and SharedPreferences. It provides a clear understanding of how different storage methods work and when to use them.

