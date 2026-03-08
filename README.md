# GABN

# Blind Assist Navigator (GABN)

An AI-powered mobile assistive application designed to help **visually impaired individuals navigate their surroundings safely using a smartphone camera**.

Unlike many accessibility tools that require users to manually capture photos or rely on expensive hardware, this system continuously processes **live camera feed in real time** to detect obstacles and provide navigation assistance.

The application converts visual information into **audio instructions and haptic feedback**, allowing users to understand their surroundings without needing to see the screen.

---

# Problem Statement

Millions of visually impaired individuals face difficulties navigating unfamiliar environments safely.

Existing assistive technologies often:

- Require expensive hardware
- Provide delayed feedback
- Require manual interaction

This project aims to build an **affordable, smartphone-based real-time navigation assistant** that improves mobility and independence.

---

# Key Features

## Real-Time Obstacle Detection
The application continuously analyzes live camera input to detect obstacles such as:

- Walls
- Steps
- Vehicles
- Pedestrians
- Objects blocking the path

Users receive **instant alerts through audio and vibration feedback**.

---

## Audio Navigation Assistance
Detected obstacles and navigation instructions are communicated using **voice feedback**.

Example alerts:
- “Obstacle ahead”
- “Turn slightly left”
- “Path clear”

---

## Haptic Feedback System
The application uses **vibration patterns** to notify users when obstacles are nearby.

This ensures accessibility even in **noisy environments**.

---

## SOS Emergency Feature
The system includes an **SOS emergency button** that allows users to quickly alert emergency contacts.

Possible actions include:

- Sending live location
- Triggering an emergency call
- Notifying trusted contacts

---

## Multilingual Accessibility
Language translation support can be integrated using services such as **Bhashini** to make the application accessible to users in multiple languages.

---

# Technology Stack

### Mobile Application
- Flutter

### Computer Vision / AI
- Google ML Kit
- TensorFlow Lite (optional)
- OpenCV

### Device Features
- Smartphone Camera API
- Vibration API
- GPS / Location services

### Voice Assistance
- Text-to-Speech (TTS)
- Voice guidance system

### Translation Support (Optional)
- Bhashini language APIs

---

# System Workflow

The system operates using the following pipeline:

1. Smartphone camera captures **live video feed**
2. Frames are processed using **computer vision models**
3. Objects and obstacles are detected
4. Distance and direction are estimated
5. Information is converted into:
   - Audio instructions
   - Haptic vibration feedback
6. The user adjusts movement accordingly

---

# Project Structure

blind_assist_app
│
├ android
├ ios
├ lib
├ linux
├ macos
├ web
├ windows
├ test
│
├ .gitignore
├ .metadata
├ analysis_options.yaml
├ pubspec.yaml
├ pubspec.lock
├ README.md

---

# Installation Guide

## Prerequisites

Install the following tools before running the project:

- Flutter SDK
- Android Studio or VS Code
- Git
- Android Emulator or Physical Device

---

## Clone the Repository

```
git clone https://github.com/YOUR_GITHUB_USERNAME/blind_assist_app.git
```

Navigate into the project folder:

```
cd blind_assist_app
```

---

## Install Dependencies

```
flutter pub get
```

---

## Run the Application

```
flutter run
```

---

# Future Improvements

Planned enhancements include:

- Indoor navigation support
- Advanced object distance estimation
- AI-based path prediction
- Smart cane hardware integration
- Real-time navigation mapping
- Improved obstacle classification models

---

# Contributors

Project developed by:

Josh
Rohith 
Riduvarshini
Ashmit 
Additional contributors may include collaborators involved in development and testing.

---

# License

This project is intended for **educational and research purposes**.

---

# Acknowledgements

This project draws inspiration from research in:

- Computer vision accessibility tools
- AI-based navigation systems
- Assistive technologies for visually impaired individuals

---

# Project Status

Active Development

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
