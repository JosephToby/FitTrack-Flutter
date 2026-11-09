# FitTrack – Workout Recording & Personal Analysis App

FitTrack is a modern fitness tracking application built using Flutter and Dart. It helps users record their workouts, monitor fitness activities, and understand their progress through personal analytics and visual reports.

## Features

- **Dashboard:** View workout statistics and recent activities.
- **Workout Management:** Add, edit, search, filter, and delete workouts.
- **Personal Analytics:** Monitor workout frequency, calories, duration, and progress.
- **Weekly Progress:** Visualize workout activity through charts.
- **Local Database:** Store workout records persistently using Hive.
- **Dark UI:** Clean and modern dark-themed interface.
- **Navigation:** Easy navigation between application screens.

## Tech Stack

| Technology | Purpose |
|---|---|
| Flutter | Cross-platform application development |
| Dart | Programming language |
| Hive | Local NoSQL database |
| Material Design | User interface |
| VS Code | Development environment |

## Application Structure

```text
lib/
├── main.dart
├── models/
│   └── workout.dart
├── screens/
│   ├── main_screen.dart
│   ├── dashboard_screen.dart
│   ├── workout_screen.dart
│   ├── analytics_screen.dart
│   ├── profile_screen.dart
│   └── add_workout_screen.dart
├── services/
│   └── database_service.dart
├── theme/
│   └── app_theme.dart
└── widgets/
```

## Getting Started

### Prerequisites

- Flutter SDK
- Dart SDK
- Android Studio or VS Code

### Installation

1. Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/FitTrack-Flutter.git
```

2. Navigate to the project:

```bash
cd FitTrack-Flutter
```

3. Install dependencies:

```bash
flutter pub get
```

4. Run the application:

```bash
flutter run
```

## Database

FitTrack uses Hive for local data persistence. Workout records are stored locally on the device.

## Future Enhancements

- User authentication and cloud synchronization
- Fitness goals and achievements
- Advanced workout reports
- Wearable device integration
- Play Store release

## Author

Developed as a personal Flutter application project.
