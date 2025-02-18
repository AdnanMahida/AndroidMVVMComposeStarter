# Android MVVM Jetpack Compose App

## 📌 Overview
This project is an **Android application** built using **Jetpack Compose** and the **MVVM architecture**. It includes essential libraries such as **Hilt for Dependency Injection, Retrofit for API calls, Room for local database storage, and WorkManager for background tasks**.

---

## 📦 Dependencies & Versions
Below are the key dependencies and their respective versions used in this project:

| Library                        | Version     |
|--------------------------------|------------|
| AGP (Android Gradle Plugin)    | 8.8.0      |
| Kotlin                         | 2.0.21     |
| Compose BOM                    | 2025.01.01 |
| Coil (Image Loading)           | 2.6.0      |
| Hilt Navigation Compose        | 1.2.0      |
| Core KTX                       | 1.15.0     |
| Activity Compose               | 1.10.0     |
| Lifecycle Runtime KTX          | 2.8.7      |
| Navigation Compose             | 2.8.6      |
| Retrofit (Networking)          | 2.11.0     |
| Gson Converter (JSON Parsing)  | 2.11.0     |
| Room (Local Database)          | 2.6.1      |
| Timber (Logging)               | 5.0.1      |
| OkHttp Logging Interceptor     | 4.12.0     |
| WorkManager KTX                | 2.10.0     |
| Security Crypto                | 1.1.0-alpha06 |
| AppCompat                      | 1.7.0      |
| JUnit (Testing)                | 4.13.2     |
| Espresso (UI Testing)          | 3.6.1      |

---

## 📜 Project Modules
This project uses the following **core libraries**:

- **Jetpack Compose**: Modern UI Toolkit
- **Hilt**: Dependency Injection
- **Retrofit**: API Handling
- **Room**: Local Database
- **WorkManager**: Background Tasks
- **Timber**: Logging Utility
- **Security Crypto**: Secure Storage

---

## 🚀 Features Implemented
- MVVM Architecture
- API Calls using Retrofit + Gson Converter
- Local Database with Room
- Navigation using Jetpack Navigation Compose
- Dependency Injection using Hilt
- Background Tasks using WorkManager
- Secure data storage with AndroidX Security Crypto

---

## 📌 Setup & Installation
1. **Clone the repository:**
   ```sh

   git clone https://github.com/AdnanMahida/AndroidMVVMComposeStarter.git 
   cd AndroidMVVMComposeStarter

   ```
2. **Open the project in Android Studio.**
3. **Sync Gradle:** Click `Sync Now` when prompted.
4. **Run the app on an emulator or physical device.**

---

## 🛠️ Build & Run
This project is configured with **Gradle Version Catalog**, making dependency management easier. To build and run:

```sh
./gradlew assembleDebug
```

For a **release build:**

```sh
./gradlew assembleRelease
```

---

## 👨‍💻 Code Structure
- `ui/` → Jetpack Compose UI Components
- `viewmodel/` → ViewModels following MVVM
- `repository/` → Repository Layer
- `network/` → Retrofit API Services
- `database/` → Room Database Implementation

Done <3 Happy Coding
