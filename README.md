# To-Do List App

A simple, clean to-do list app built with Flutter. Add, complete, and delete
tasks — everything is saved on-device so your list is still there next time
you open the app.

## Features

- Add new tasks
- Mark tasks as done (with a strikethrough)
- Delete a task by tapping the X or swiping it away
- Tasks persist between app restarts (via `shared_preferences`)

## Run locally

Requires the Flutter SDK ([install guide](https://docs.flutter.dev/get-started/install)).

```bash
flutter pub get
flutter run
```

## Project structure

```
lib/
  main.dart      # App entry point, UI, and task logic
pubspec.yaml      # Dependencies
```

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit: To-Do list app"
git branch -M main
git remote add origin https://github.com/<your-username>/todo-app.git
git push -u origin main
```
