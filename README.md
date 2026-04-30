#  API Explorer Flutter App

##  Project Title

API Explorer App using Flutter (Android Development ALA)

---

##  Project Description

This project is developed as part of the Android Development ALA. The application demonstrates how to integrate a public REST API into a Flutter application, fetch JSON data from the internet, par[...] 

The app connects to an online API and dynamically loads images and titles, making it a real-time data-driven application.

---

##  Objectives

* Understand REST API integration in Flutter
* Learn JSON data parsing
* Implement asynchronous programming using FutureBuilder
* Design responsive UI using GridView
* Upload and manage project using GitHub

---

##  Features

*  Fetch data from live REST API
*  Parse JSON data into Dart objects
*  Display images with titles
*  GridView layout for better UI
*  Fast and responsive interface
*  Real-time data loading

---

##  Technologies Used

* Flutter
* Dart
* REST API
* HTTP Package
* Android Studio / VS Code

---

##  API Used

https://jsonplaceholder.typicode.com/photos

---

##  Project Structure

lib/
├── main.dart
├── models/
│   └── photo.dart
├── services/
│   └── api_service.dart
└── screens/
└── home_screen.dart

---

##  How It Works

1. The app sends a request to the REST API
2. The API returns JSON data
3. JSON is converted into Dart objects
4. Data is displayed using GridView
5. Images are loaded from network URLs

---

##  Installation & Setup

### Step 1: Clone Repository

git clone https://github.com/your-username/api_explorer_app.git

### Step 2: Navigate to Project

cd api_explorer_app

### Step 3: Install Dependencies

flutter pub get

### Step 4: Run Application

flutter run

---

##  Output Screens


The app displays a list of photos with title and images using GridView layout.
<img width="960" height="506" alt="image" src="https://github.com/user-attachments/assets/d6afab46-e528-4f29-a074-f2797a6b7136" />

* Displays list of images with titles
* Grid layout UI
* Dynamic data from API

(Add screenshots here for better presentation)

---

##  Testing

* Tested on Android Emulator
* Tested on Chrome (Flutter Web)
* Handles API loading and errors

---

##  Challenges Faced

* Handling large API data
* Managing asynchronous data
* Fixing UI overflow issues
* Debugging network errors

---

##  Future Improvements

*  Search functionality
*  Dark mode
*  Favorites feature
*  Detail screen for each item
*  Advanced animations

---

##  Learning Outcomes

* API integration in Flutter
* JSON parsing and data modeling
* UI design with GridView
* GitHub project management

---

##  License

This project is for educational purposes only.
