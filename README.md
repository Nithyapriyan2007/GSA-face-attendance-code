# GSA Face Attendance System

### AI-Powered Facial Recognition Attendance Application for Global Sports Academy

GSA Face Attendance is a dedicated Android application developed for **Global Sports Academy (GSA)** to simplify and modernize student attendance management using facial recognition technology.

The system is designed to identify registered students, record their attendance automatically, and integrate with the academy's backend infrastructure.

The objective is to build a reliable, secure and user-friendly attendance solution that reduces manual work and improves attendance accuracy.

---

## Project Overview

The GSA Face Attendance System combines mobile application development, facial recognition, backend API integration and secure local data storage.

The application is designed to operate on a dedicated Android smartphone at the academy.

### Key Features

- **Facial Recognition:** Identify registered students using facial recognition.
- **Automated Attendance:** Record attendance without manual entry.
- **Student Identification:** Associate recognized faces with registered student records.
- **Face Verification:** Integrate face-quality and liveness verification capabilities.
- **Backend Integration:** Communicate with the academy's backend APIs.
- **Offline Support:** Designed to support local attendance storage when network connectivity is unavailable.
- **Data Security:** Use secure storage mechanisms for sensitive application data.
- **Android Application:** Dedicated mobile application for academy operations.

---

## Technology Stack

| Component | Technology |
|---|---|
| Mobile application | Flutter |
| Native Android integration | Kotlin |
| Facial recognition SDK | GdFace / Seeta SDK |
| Backend | API integration |
| Database | Backend database and SQL migrations |
| Local security | Android Keystore and encrypted storage |
| CI/CD | GitHub Actions |

---

## Project Architecture

```text
             GLOBAL SPORTS ACADEMY
                       |
                       |
             GSA FACE ATTENDANCE
                 ANDROID APP
                       |
              +--------+--------+
              |                 |
         Flutter UI       Native Android
              |                 |
              |           Kotlin Bridge
              |                 |
              |          Face Recognition
              |             Engine
              |                 |
              +--------+--------+
                       |
                Attendance Data
                       |
                Backend API
                       |
                   Database
                       |
              Attendance Records
```

---

## Repository Structure

```text
GSA-face-attendance-code/
│
├── .github/
│   └── workflows/
│
├── apps/
│   ├── api/
│   │   ├── migrations/
│   │   ├── src/
│   │   └── tests/
│   │
│   ├── face_attendance/
│   │   ├── android/
│   │   ├── assets/
│   │   ├── lib/
│   │   ├── test/
│   │   └── tools/
│   │
│   └── web/
│       └── src/
│
├── README.md
└── README-PUSH.md
```

---

## Installation and Setup

### Requirements

- Android Studio
- Flutter SDK
- Dart SDK
- Android SDK
- JDK compatible with the Android Gradle configuration
- Git
- Access to the required backend services and licensed facial recognition SDK components

### Clone the Repository

```bash
git clone https://github.com/Nithyapriyan2007/GSA-face-attendance-code.git
```

Navigate to the project:

```bash
cd GSA-face-attendance-code/apps/face_attendance
```

Install Flutter dependencies:

```bash
flutter pub get
```

Check the Flutter environment:

```bash
flutter doctor
```

Run the application on a connected Android device:

```bash
flutter run
```

*Note: Backend configuration, Android SDK configuration and any required face-recognition model files must be completed before the application can run successfully.*

---

## Security and Privacy

Student facial information is sensitive biometric data. The system is intended to handle such information responsibly.

Security considerations include:

- Secure handling of student information.
- Encrypted storage of sensitive local data.
- Controlled access to attendance records.
- Secure backend communication.
- Protection of authentication credentials.
- Appropriate authorization for biometric data collection and processing.

The academy should obtain appropriate consent and establish a biometric-data retention and deletion policy before deployment.

---

## Development Status

**Project:** GSA Face Attendance

**Platform:** Android

**Development:** Active development and integration.

The application is being developed with a focus on facial recognition, attendance automation, backend connectivity, security and real-world deployment.

Features and deployment readiness are subject to testing and verification.

---

## Future Enhancements

- Real-time attendance dashboard.
- Parent notification integration.
- Automated entry and exit notifications.
- Advanced anti-spoofing verification.
- Attendance analytics and reports.
- Improved offline synchronization.
- Multi-device support.
- Administrative management portal.

---

## Project Information

**Project Name:** GSA Face Attendance

**Organization:** Global Sports Academy

**Project Category:** Artificial Intelligence / Mobile Application Development

**Primary Platform:** Android

**Developer:** Nithyapriyan R

**GitHub Repository:**  
https://github.com/Nithyapriyan2007/GSA-face-attendance-code

---

## License

This project contains third-party libraries and SDK components. Their respective licenses and redistribution requirements must be respected.

The licensing terms of the individual components apply.

---

### Built for Global Sports Academy

**Making attendance smarter, faster and more reliable through technology.*
