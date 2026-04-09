# 📰 News Explorer App

A Flutter mobile application that fetches and displays news from a public REST API.  
The app includes authentication, search, filtering, and a responsive user interface.

## 🚀 Features

- 🔐 Firebase Authentication (Email/Password & Google Sign-In)
- 📰 Browse top headlines and news by category
- 🔍 Search and filter news articles
- 👤 User session handling (auto-login)
- 📱 Responsive UI for different screen sizes
- ⚡ Smooth loading with skeleton screens
- 🖼️ Optimized image loading

## 🛠️ Tech Stack

- Flutter & Dart
- State Management: BLoC (Cubit)
- Firebase Authentication
- REST API
- Dio
- cached_network_image
- skeletonizer

## 🔗 API

This app uses a public news API.  
👉 Please replace the API key with your own from https://newsapi.org/

## ⚙️ Setup

```bash
# Clone the repo
git clone https://github.com/mai450/News_App_Task.git

# Install dependencies
flutter pub get

# Run the app
flutter run

## Project Structure
lib/
├─ core/
│  ├─ errors/
│  ├─ helper_functions/
│  ├─ services/
│  └─ utils/
│
├─ features/
│  ├─ auth/
│  ├─ home/
│  ├─ search/
│  ├─ splash/
│  └─ start/
├─ firebase_options.dart
└─ main.dart

## Developer ##
# Mai Awad Sadat
Mobile Application Developer using Flutter
Email: maiawad450@gmail.com
GitHub: https://github.com/mai450
