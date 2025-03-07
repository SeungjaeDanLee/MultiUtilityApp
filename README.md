# 📱 MultiUtilityApp

## 📌 Project Overview

```md
MultiUtilityApp is an all-in-one utility application designed to practice and explore various Jetpack Compose features. This app provides multiple simple yet useful functionalities within a single application, leveraging Compose's capabilities.
```

## ✅ Features

```md
- **To-Do List** → Add and remove tasks easily
- **Notepad** → Write and save simple notes
- **Timer** → Start and stop a timer
- **Counter** → Increment and decrement numbers
- **Image Gallery** → Display sample images
```

## 📌 Jetpack Compose Elements

### To-Do List
```kotlin
LazyColumn, TextField, Button, Checkbox, remember, mutableStateOf
```

### Notepad
```kotlin
TextField, Scaffold, FloatingActionButton, Card, LazyColumn
```

### Timer
```kotlin
LaunchedEffect, produceState, Button, Text
```

### Counter
```kotlin
remember, mutableStateOf, Button, Text
```

### Image Gallery
```kotlin
LazyColumn, Image, remember
```

## 📌 App Structure

### Main Screen
```md
- Displays a list of buttons to navigate to each feature using `LazyColumn`.
```

### Feature Screens
```md
- Implements UI using `Scaffold`, including a title bar and Floating Action Button (`FAB`) where applicable.
```

### State Management
```md
- Utilizes `remember`, `mutableStateOf`, and `LaunchedEffect` to manage UI state efficiently.
```

```md
This project serves as an excellent practice ground for Jetpack Compose development while creating a functional and user-friendly utility app.
```
