# Namma-Yantra Share

A tractor marketplace application for farmers and owners.

## Features
- **Farmer Side**: Browse available machines (Tractors, Harvesters, etc.), calculate rental costs, and book machines.
- **Owner Side**: Manage machine inventory, view and respond to booking requests, and track analytics.
- **Real-time Integration**: Firebase integration for authentication and data storage.

## 📂 Project Structure
```text
├── android/                   # Android App Source
│   ├── app/
│   │   ├── src/main/
│   │   │   ├── java/          # Kotlin Source (Compose)
│   │   │   ├── AndroidManifest.xml
│   │   │   └── res/           # Layout/Theme Resources
│   │   └── build.gradle       # App Dependencies
│   └── build.gradle           # Project Config
├── web-prototype/             # Web Application Prototype
│   ├── app.js                 # Frontend Logic
│   ├── index.html             # UI Structure
│   ├── style.css              # Custom Styling
│   └── package.json           # Web Build Config
├── PRD.md                     # Product Requirements Document
└── README.md                  # Project Documentation
```

## 🛠️ Tech Stack

### Web Prototype
1. Go to the [Firebase Console](https://console.firebase.google.com/).
2. Create a new project named "Namma-Yantra Share".
3. Add a Web App to the project.
4. Copy the `firebaseConfig` object and paste it into `web-prototype/app.js`.
5. Enable **Email/Password Authentication** and **Cloud Firestore** in the Firebase console.

### Android App
1. Add an Android App to your Firebase project.
2. Register the package name: `com.nammayantrashare.app`.
3. Download `google-services.json` and place it in the `android/app/` directory (create the directory if needed).
4. Sync the project with Gradle files.

## How to Run

### Web Prototype
Open `web-prototype/index.html` in any modern web browser.

### Android App
The source files are located in the `android/` directory. You can import them into a standard Android Studio project structure.
