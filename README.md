
# 🎓 Campus Event Discovery App

## 📌 Project Overview

The **Campus Event Discovery App** is a mobile application developed using **Flutter** to help students easily discover, explore, and participate in campus events.
It provides a centralized platform where students can browse upcoming events, view event details, register for events, and receive notifications about new or trending activities happening on campus.

This application aims to **increase student engagement** and improve awareness of campus events through a user-friendly mobile interface.

---

## 🚀 Features

* 🔐 **User Authentication**

  * Sign up and login using **Firebase Authentication**

* 📅 **Browse Events**

  * View a list of upcoming campus events
  * View detailed information for each event

* 🔍 **Search & Filter**

  * Search events by name
  * Filter events by category

* 🔔 **Notifications**

  * Receive notifications for new or trending campus events

---

## 🛠️ Technology Stack

### Frontend

* **Flutter**
* **Dart**

### Backend / Services

* **Firebase Authentication** – user login & signup
* **Firebase Cloud Firestore** – event data storage
* **Firebase Cloud Messaging (FCM)** – push notifications

### Platforms Supported

* Android


---

## 📂 Project Structure

```
flutter_event_app/
│
├── lib/
│   ├── main.dart          # App entry point
│   ├── screens/           # UI screens (login, home, event details)
│   ├── widgets/           # Reusable UI components
│   ├── models/            # Data models (Event, User)
│   └── services/          # Firebase & backend services
│
├── assets/                # Images and icons
├── android/               # Android-specific files
├── ios/                   # iOS-specific files
├── pubspec.yaml           # Dependencies & assets
└── README.md              # Project documentation
```

---

## ⚙️ Installation & Setup

### Prerequisites

* Flutter SDK installed
* Android Studio or VS Code
* Firebase project setup

### Steps to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/Srivaxshana/flutter_event_app.git
```

2. Navigate to the project directory:

```bash
cd flutter_event_app
```

3. Install dependencies:

```bash
flutter pub get
```

4. Run the application:

```bash
flutter run
```

---

## 🔑 Firebase Configuration

* Create a Firebase project
* Enable **Email/Password Authentication**
* Create a **Cloud Firestore** database
* Add `google-services.json` (Android) / `GoogleService-Info.plist` (iOS)

---

## 🎯 Future Enhancements

* Event registration & ticketing
* Admin panel for event creation
* Calendar integration
* User profile management

---



