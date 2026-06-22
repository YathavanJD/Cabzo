# 🚗 Cabzo — Car Booking Mobile Application

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat&logo=androidstudio&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

> An Android-based ride booking application with real-time ride requests, tracking, and mobile-optimized UI.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Author](#author)

---

## 📖 About the Project

Cabzo is an Android mobile application that simulates a ride booking system similar to popular cab services. Users can request rides, track their ride status, and manage their bookings — all through a clean, mobile-optimized interface.

The app was developed using Java and Android Studio, showcasing skills in Android development, UI/UX design for mobile, and ride management logic.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📍 Ride Request | Users can request a ride by entering pickup and drop-off locations |
| 🚘 Ride Management | View active, pending, and completed ride requests |
| 📡 Ride Tracking | Track ride status in real time within the app |
| 📱 Mobile-Optimized UI | Clean, responsive interface designed for Android devices |
| 👤 User Profile | Manage personal account and ride history |
| 🔐 Authentication | Secure login and registration for passengers |

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Language | Java |
| IDE | Android Studio |
| UI Framework | Android XML Layouts |
| Local Database | SQLite |
| Min SDK | Android 8.0 (API 26) |
| Target SDK | Android 13 (API 33) |

---

## ⚙️ Installation

### Prerequisites
- Android Studio (latest version)
- Java JDK 11+
- Android device or emulator (API 26+)

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/YathavanJD/Cabzo.git

# 2. Open Android Studio
# File → Open → Select the cloned project folder

# 3. Wait for Gradle sync to complete

# 4. Run the application
# Click the green 'Run' button or press Shift + F10
# Select your emulator or connected Android device
```

### Build APK

```bash
# In Android Studio:
# Build → Build Bundle(s) / APK(s) → Build APK(s)
# APK will be generated in: app/build/outputs/apk/debug/
```

---

## 🚀 Usage

### Passenger
1. Register or log in to your account
2. Enter your pickup location and destination
3. Request a ride and wait for confirmation
4. Track your ride status in real time
5. View completed ride history in your profile

---

## 📁 Project Structure

```
Cabzo/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/cabzo/
│   │   │   │   ├── MainActivity.java          # App entry point
│   │   │   │   ├── LoginActivity.java         # User login
│   │   │   │   ├── RegisterActivity.java      # User registration
│   │   │   │   ├── BookRideActivity.java      # Ride booking screen
│   │   │   │   ├── TrackRideActivity.java     # Ride tracking screen
│   │   │   │   ├── RideHistoryActivity.java   # Past rides
│   │   │   │   ├── ProfileActivity.java       # User profile
│   │   │   │   └── DatabaseHelper.java        # SQLite helper
│   │   │   │
│   │   │   ├── res/
│   │   │   │   ├── layout/                    # XML UI layouts
│   │   │   │   ├── drawable/                  # Icons and images
│   │   │   │   └── values/                    # Colors, strings, styles
│   │   │   │
│   │   │   └── AndroidManifest.xml
│   │
│   └── build.gradle
│
├── gradle/
├── build.gradle
└── README.md
```

---

## 👨‍💻 Author

**Loganathan Yathavan**
- 📧 loganathanyathavan@gmail.com
- 🌐 [Portfolio](https://yathavanjd.github.io/Yathavan_Portfolio/)
- 💼 [LinkedIn](https://www.linkedin.com/in/yathavanloganathan03)
- 🐙 [GitHub](https://github.com/YathavanJD)

---

> ⭐ If you found this project useful, please consider giving it a star!
