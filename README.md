📝 Task Manager App
A simple and lightweight Task Management App built using Flutter. This app allows users to:

✅ Add new tasks

🗑️ Remove tasks

☑️ Mark tasks as completed

💾 Save tasks persistently using SharedPreferences

📱 Features
Beautiful and clean UI with Material Design

Add tasks via dialog input

Toggle task status with a checkbox

Swipe to delete tasks

Persistent storage using shared_preferences — your tasks are saved even after the app is closed

🚀 Getting Started
Prerequisites
Flutter SDK installed

A code editor like VS Code or Android Studio

Installation
Clone the repo:
git clone https://github.com/Labeebkhan/task_managment.git
cd task_managment

Install dependencies:
flutter pub get

Run the app:
flutter run

🧠 How It Works
Task Model
Each task is an object with a title and a isDone boolean flag.

Local Storage
Tasks are stored locally using SharedPreferences by serializing them to JSON strings.

UI
The main screen displays a list of tasks using a ListView. Tasks can be added, toggled as complete, and removed individually or by swiping.

🧩 Folder Structure
lib/
├── main.dart         # App entry point and UI

📦 Dependencies
Flutter
shared_preferences

🖼️ Screenshot
(You can insert a screenshot here showing the UI)

✍️ Author
Your Name – @yourusername

📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

