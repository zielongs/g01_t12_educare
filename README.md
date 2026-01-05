# EduCare Flutter Mobile Application

## Description
EduCare is a Flutter-based mobile application developed as a group project. The application supports multiple user roles, including Admin, Tutor, and Student, and provides role-based functionalities for managing schedules, sessions, and learning activities.

---

## Installation

### Prerequisites
- Flutter SDK (version 3.x or later)
- Dart SDK (included with Flutter)
- Android Studio or Visual Studio Code
- Android Emulator or physical Android device

### Check Flutter Installation
```bash
flutter --version
```

---

## Setup

### Clone Repository
```bash
git clone <repository-url>
cd <project-folder>
```

### Download ZIP
1. Click **Code → Download ZIP** from GitHub  
2. Extract the ZIP file  
3. Open the folder that contains `pubspec.yaml` in VS Code or Android Studio  

---

## Usage

### Run the Application
1. Open a terminal in the project root directory
2. Run the following commands:
```bash
flutter clean
flutter pub get
flutter run
```

### Application Usage
1. Launch the application.
2. Select a role from the role selection screen (**Admin**, **Tutor**, or **Student**).
3. Navigate through the system using the available buttons and menus.

#### Admin
- Manage tutor schedules and session details.
- Update date, time, and subject information.
- Select replacement tutors either manually or using AI recommendations.
- Save all updates using the **Save Changes** button.

#### Tutor
- View assigned schedules and sessions.
- Check session details provided by the administrator.

#### Student
- View available sessions and learning schedules.
- Access information relevant to enrolled sessions.

---

## Project Structure
```txt
lib/
├── main.dart
├── screens/
├── services/
└── widgets/
```

---

## Troubleshooting

- **Not a Flutter project**  
  Ensure the opened folder contains `pubspec.yaml`.

- **Dependency or build errors**  
  Run:
```bash
flutter clean
flutter pub get
```

---

## License
This project is developed for academic purposes only.
