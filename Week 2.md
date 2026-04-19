# 🎓 Week 2 – Navigation, Forms & Authentication Flow

### Flutter Mobile App Development (Industry-Oriented)

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-Mobile%20Development-02569B?logo=flutter&logoColor=white">
  <img src="https://img.shields.io/badge/Dart-Programming-0175C2?logo=dart&logoColor=white">
  <img src="https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-success">
  <img src="https://img.shields.io/badge/Mode-Theory%20%2B%20Practical-orange">
</p>

<p align="center">
<b>From Static UI to Interactive Mobile Applications</b><br>
Learn how modern apps move between screens, collect data, validate input, and manage authentication professionally.
</p>

---

<img width="1919" height="994" alt="web" src="https://github.com/user-attachments/assets/213eb8e8-c4f6-401b-b4bc-898107ffebc7" />
<img width="1344" height="2992" alt="Screenshot_1776594275" src="https://github.com/user-attachments/assets/67f92cbe-dfb3-4caf-92bc-37ab78a7868e" />


# 📘 Week Information

| Item             | Details                                 |
| ---------------- | --------------------------------------- |
| Week             | 2                                       |
| Session Title    | Navigation, Forms & Authentication Flow |
| Duration         | 2.5 Hours                               |
| Level            | Final Year / Undergraduate              |
| Mode             | Theory + Live Coding + Practical        |
| Technology Stack | Flutter + Dart                          |
| Focus Area       | Multi-Screen Interactive Applications   |

---

# 📖 Module Overview

This week introduces students to the transition from static interfaces into real interactive mobile applications.

Students will learn how professional Flutter apps:

* Navigate between multiple screens
* Build structured forms for data collection
* Validate user input correctly
* Implement login and registration flows
* Improve user experience through clean navigation
* Organize projects using scalable structure

These concepts are foundational for production-level mobile development.

---

# 🎯 Learning Objectives

By the end of this session, students should be able to:

* Understand Flutter navigation systems
* Move users between screens efficiently
* Build professional forms using Flutter widgets
* Apply validation rules to user input
* Create authentication flows
* Organize project files cleanly
* Improve usability and user experience

---

# 🧠 Learning Outcomes

Students will be able to:

1. Use Navigator.push() and Navigator.pop() correctly
2. Implement Named Routes professionally
3. Build Login → Register → Home flows
4. Use Form and TextFormField widgets
5. Validate email and password inputs
6. Manage input fields with controllers
7. Apply clean project architecture
8. Build user-friendly authentication screens

---

# 🛠️ Technologies Used

| Category     | Tool                     |
| ------------ | ------------------------ |
| Framework    | Flutter                  |
| Language     | Dart                     |
| IDE          | VS Code / Android Studio |
| UI Library   | Material Design          |
| Navigation   | Navigator API            |
| Forms        | Flutter Form Widgets     |
| Validation   | Built-in Validators      |
| Architecture | Feature-Based Structure  |

---

# 🗂️ Weekly Modules

# 📍 Module 1: Navigation Systems

## Concept

Navigation is the process of moving users between screens inside an application.

## Example Flow

Login → Home → Profile → Settings

## Why It Matters

* No user journey
* Poor usability
* Confusing app flow

## Basic Navigation Example

```dart
Navigator.push(
 context,
 MaterialPageRoute(
   builder: (_) => HomeScreen(),
 ),
);
```

## Go Back

```dart
Navigator.pop(context);
```

---

# 📍 Module 2: Named Routes (Professional Navigation)

## Why Named Routes?

Large apps require centralized route management.

## Example Routes

/login
/register
/home
/profile
/settings

## Benefits

* Cleaner code
* Easier maintenance
* Better scalability
* Faster development

---

# 📍 Module 3: Forms Engineering

## Concept

Forms are systems used to collect structured user data.

## Main Widgets

* Form
* TextFormField
* GlobalKey<FormState>

## Common Inputs

* Email
* Password
* Full Name
* Phone Number

---

# 📍 Module 4: TextEditingController

Used to manage and read input fields.

```dart
final emailController = TextEditingController();
```

## Benefits

* Read entered text
* Clear fields
* Update values dynamically

---

# 📍 Module 5: Validation Engineering

## Why Validation Matters

Validation protects:

* User experience
* Data quality
* Security
* Backend systems

## Required Field Example

```dart
if(value!.isEmpty){
 return 'Required field';
}
```

## Email Validation Example

```dart
if(!value.contains('@')){
 return 'Invalid email';
}
```

## Password Rules

* Minimum 6 characters
* Strong password recommended

---

# 📍 Module 6: Authentication Flow Design

## Login Flow

Login Screen
↓
Validate Input
↓
Success
↓
Home Screen

## Register Flow

Login
↓
Create Account
↓
Register
↓
Back to Login

## Why Important

Authentication protects user access and controls sessions.

---

# 📍 Module 7: Clean Project Structure

```text
lib/
 ├── screens/
 │   ├── login_screen.dart
 │   ├── register_screen.dart
 │   └── home_screen.dart
 │
 ├── widgets/
 │   ├── custom_text_field.dart
 │   └── primary_button.dart
 │
 ├── routes/
 └── main.dart
```

## Benefits

* Easier teamwork
* Cleaner codebase
* Better scalability
* Faster debugging

---

# 💻 In-Class Practical Session

Students will build:

* Login Screen
* Register Screen
* Home Screen
* Navigation Flow
* Validation Rules
* Clean UI Layout

---

# 📝 Assignment – Authentication App

## Student Task

Create a professional Flutter Authentication Application.

## Required Screens

### Login Screen

* Email field
* Password field
* Login button
* Register link

### Register Screen

* Full Name
* Email
* Password
* Confirm Password
* Register button

### Home Screen

* Welcome text
* Logout button (optional)

---

# 📌 Functional Requirements

## Navigation Flow

Login ↔ Register
Login → Home

## Validation Rules

* All fields required
* Valid email format
* Password minimum 6 characters
* Passwords must match

---

# ⚠️ Common Mistakes to Avoid

* Using TextField instead of TextFormField
* No validation rules
* Messy navigation logic
* Hardcoded values
* Poor spacing and UI design
* Unorganized folders

---

# 📚 Recommended Resources

* Flutter Official Documentation
  [https://docs.flutter.dev/](https://docs.flutter.dev/)

* Navigation Basics
  [https://docs.flutter.dev/cookbook/navigation/navigation-basics](https://docs.flutter.dev/cookbook/navigation/navigation-basics)

* Forms Validation Guide
  [https://docs.flutter.dev/cookbook/forms/validation](https://docs.flutter.dev/cookbook/forms/validation)

* Pub.dev Packages
  [https://pub.dev/](https://pub.dev/)

* Firebase
  [https://firebase.google.com/](https://firebase.google.com/)

---

# 🚀 Next Week Preview

## Week 3 – State Management & Architecture

Students will learn:

* What is State
* Why apps become messy
* Clean scalable architecture
* Provider / Bloc / Riverpod basics / Getx

---

# 👨‍🏫 Instructor Message

Beautiful UI attracts users.
Functional flow keeps users.

---

# ⭐ Developer Mindset

Build. Break. Debug. Improve. Repeat.

---

