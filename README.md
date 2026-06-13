# ApexPlanet Android Development Internship - Task 1

## 🚀 Project Overview
This repository contains the deliverables for **Task 1: Onboarding and Environment Setup** of my Android Development Internship at **ApexPlanet Software Pvt Ltd**. The primary objective was to configure a robust, industry-standard development environment and deploy a native application successfully.

---

## 🛠️ Tech Stack & Environment Setup
- **IDE:** Android Studio (Latest Stable Version)
- **Language:** Kotlin / Java
- **Build System:** Gradle (Kotlin DSL)
- **Version Control:** Git & GitHub
- **Target Device:** Physical Android Device (via USB Debugging)

---

## 📈 Key Activities Completed

### 1. Onboarding & Workspace Configuration
- Attended orientation sessions to align with company workflows and internship goals.
- Connected with team members and technical mentors.

### 2. Environment Configuration
- Installed and configured **Android Studio** along with the necessary Android SDK tools and platforms.
- Setup **Git Bash** for future version control automation.
- Configured a dedicated project directory on the local workspace for structured development.

### 3. Compilation & Deployment
- Created an initial native Android project skeleton using the **Empty Views Activity** template.
- Successfully completed the initial **Gradle Sync** and indexed project dependencies.
- Configured **Developer Options** and **USB Debugging** on a physical Android handset to run the application directly, bypassing emulator latency.
- Deployed the boilerplate "Hello World" application successfully on the hardware device.

---

## 📂 Project Structure Snapshot
```text
MyFirstApp/
│
├── app/                  # Main application module
│   ├── src/              # Source files (main, test, androidTest)
│   │   └── main/
│   │       ├── java/     # Backend Logic (MainActivity)
│   │       └── res/      # UI Layouts & Resources (activity_main.xml)
│   └── build.gradle.kts  # Module-level build configuration
│
└── build.gradle.kts      # Project-level build configuration
