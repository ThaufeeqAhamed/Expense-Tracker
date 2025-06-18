# 💰 Expense Manager

A simple and user-friendly Flutter application to manage your daily expenses. Built for web using Flutter and Dart.

## 🚀 Features

- Add, edit, and delete expenses
- Categorize expenses (e.g., Food, Travel, Shopping)
- Tag management
- Track and manage spending efficiently
- Responsive UI for web
- Hot reload support (with `hot_reload.sh` script)

## 🛠️ Tech Stack

- **Flutter** (Web)
- **Dart**
- **Provider** (State Management)
- **LocalStorage** (to store data locally)
- **inotify-tools & lsof** (for hot-reload script)

## 🏃 Getting Started

### Prerequisites

- Flutter SDK (version X.X.X)
- Dart SDK
- Chrome (for web testing)
- Internet connection
### Installation

1. Clone the repository
2. Get the packages:
  flutter pub get

3. Run on web
   chmod +x ./hot_reload.sh
   ./hot_reload.sh

## 📂 Project Structure
 Project Structure

lib/

├── main.dart

├── models/

├── providers/

├── screens/

└── widgets/
