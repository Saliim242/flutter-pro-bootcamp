````md id="week2-readme-final"
# 🎓 Week 2 – Navigation, Forms & Authentication Flow  
## Flutter Mobile App Development (Industry-Oriented)

<p align="center">
  <b>From Static UI to Interactive Mobile Applications</b><br>
  Learn how real-world apps move between screens, collect user data, and validate input professionally.
</p>

---

# 📘 Week Information

| Item | Details |
|------|---------|
| **Week** | 2 |
| **Session Title** | Navigation, Forms & Authentication Flow |
| **Duration** | 2.5 Hours |
| **Level** | Final Year (Undergraduate) |
| **Focus** | Multi-Screen Interactive Applications |
| **Teaching Style** | Theory + Live Coding + Practical |

---

# 📖 Week Description

This week transitions students from static user interfaces into interactive mobile applications.

Students will learn how professional mobile applications:

- Navigate between multiple screens  
- Collect user data through structured forms  
- Validate user input before submission  
- Build Login and Registration systems  
- Organize screens professionally  
- Improve user experience using clean flows  

This session introduces core interaction concepts used in production Flutter applications.

---

# 🎯 Week Objectives

By the end of this session, students will be able to:

- Understand Flutter navigation systems  
- Build screen-to-screen user flows  
- Implement professional forms  
- Validate input correctly  
- Create Login and Registration modules  
- Structure routes cleanly  
- Improve application usability  

---

# 🧠 Learning Outcomes

Students will be able to:

1. Use `Navigator.push()` and `Navigator.pop()`  
2. Implement Named Routes professionally  
3. Build Login → Register → Home flows  
4. Use `Form` and `TextFormField` widgets  
5. Apply email and password validation  
6. Use `TextEditingController` effectively  
7. Organize screens using clean architecture  
8. Build user-friendly authentication interfaces  

---

# 🛠️ Technologies Used

| Category | Tools |
|---------|------|
| Framework | Flutter |
| Language | Dart |
| IDE | VS Code / Android Studio |
| UI Components | Material Design |
| Navigation | Navigator API |
| Validation | Form System |
| Architecture | Clean Folder Structure |

---

# 📚 Week Topics & Modules

---

# Module 1: Navigation Systems in Flutter

## Theory

Navigation is the process of moving users between screens inside an application.

### Examples:

```text
Login → Home
Home → Profile
Profile → Settings
````

### Why It Matters

Without navigation:

* No user journey
* Poor usability
* No app structure

### Flutter Navigation Methods

## Direct Navigation

```dart id="2j9jgr"
Navigator.push(
 context,
 MaterialPageRoute(
   builder: (_) => HomeScreen(),
 ),
);
```

## Go Back

```dart id="dyhl0t"
Navigator.pop(context);
```

---

# Module 2: Named Routes (Professional Approach)

## Why Named Routes?

Large applications need organized route management.

### Example Routes

```text id="f7dwri"
/login
/register
/home
/profile
/settings
```

### Benefits

* Cleaner code
* Easier maintenance
* Better scalability

---

# Module 3: Forms & Input Systems

## Professional Input Handling

Flutter forms help collect structured user data.

### Main Widgets

* `Form`
* `TextFormField`
* `GlobalKey<FormState>`

### Input Examples

* Email
* Password
* Full Name
* Phone Number

---

# Module 4: TextEditingController

Used to control and read text input.

```dart id="i06x8f"
final emailController = TextEditingController();
```

### Benefits

* Read user data
* Clear fields
* Update text programmatically

---

# Module 5: Validation Engineering

## Why Validation Matters

Validation protects:

* User experience
* Data quality
* Security
* Backend systems

---

## Validation Examples

### Required Field

```dart id="ncnp3z"
if(value!.isEmpty){
 return 'Required field';
}
```

### Email Validation

```dart id="h9jh8x"
if(!value.contains('@')){
 return 'Invalid email';
}
```

### Password Validation

* Minimum 6 characters
* Strong password preferred

---

# Module 6: Authentication Flow Design

## Real-World Flow

```text id="q1kvdx"
Login Screen
   ↓
Validate Input
   ↓
Success
   ↓
Home Screen
```

### Register Flow

```text id="4u1wb7"
Login
 ↓
Create Account
 ↓
Register
 ↓
Back to Login
```

---

# Module 7: Clean Folder Structure

```text id="9n2y0r"
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

### Why It Matters

Professional developers organize projects early.

---

# 💻 In-Class Practical Session

Students will build:

✅ Login Screen
✅ Register Screen
✅ Home Screen
✅ Navigation Flow
✅ Form Validation
✅ Clean Layout

---

# 📝 Assignment – Authentication Module

## 🎯 Student Task

Build a professional Flutter Authentication App.

---

## Required Screens

### 1. Login Screen

Must include:

* Email field
* Password field
* Login button
* Register navigation link

---

### 2. Register Screen

Must include:

* Full Name
* Email
* Password
* Confirm Password
* Register button

---

### 3. Home Screen

Must display:

* Welcome text
* Logout button (optional)

---

# 📌 Functional Requirements

## Navigation

```text id="cycrl2"
Login ↔ Register
Login → Home
```

## Validation Rules

* All fields required
* Valid email format
* Password minimum 6 characters
* Passwords must match

---



# ⚠️ Common Mistakes to Avoid

* Using `TextField` instead of `TextFormField`
* No validation
* Messy navigation code
* Hardcoded values
* No spacing / poor UI
* No file organization

---

# 📚 Recommended Resources

## Flutter Official Docs

[https://docs.flutter.dev/](https://docs.flutter.dev/)

## Navigation Guide

[https://docs.flutter.dev/cookbook/navigation/navigation-basics](https://docs.flutter.dev/cookbook/navigation/navigation-basics)

## Forms Validation

[https://docs.flutter.dev/cookbook/forms/validation](https://docs.flutter.dev/cookbook/forms/validation)

## Pub.dev Packages

[https://pub.dev/](https://pub.dev/)

## Firebase

[https://firebase.google.com/](https://firebase.google.com/)

---

# 💡 Student Success Tips

* Practice daily
* Build while learning
* Understand each widget
* Use documentation
* Ask questions
* Organize code early

---

# 🚀 Next Week Preview

## Week 3 – State Management & Architecture

Students will learn:

* What is State
* Why apps become messy
* Scalable Flutter Architecture

---

# 👨‍🏫 Instructor Message

> Beautiful UI attracts users.
> Functional flow keeps users.

---

# ⭐ Mindset for Developers

> Build. Break. Debug. Improve. Repeat.

```
```
