# Student Registration Form 📝

A simple Flutter application for student registration using TextFormField widgets and form validation.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6ffd037c-27cc-4a4e-8a33-2e54728573b8" />


---

# Features ✨

- Student registration form
- Name input field
- Email input field
- Phone number input field
- Password field
- Submit button
- Snackbar message after submission
- Clean Flutter UI

---

# Tech Stack 🚀

- Flutter
- Dart

---

# Installation ⚙️

## 1. Clone Repository

```bash
git clone https://github.com/your-username/student-registration-form.git
```

## 2. Open Project

```bash
cd student-registration-form
```

## 3. Install Dependencies

```bash
flutter pub get
```

## 4. Run App

```bash
flutter run
```

---

# Project Structure 📁

```text
lib/
 ├── main.dart

```

---

# Widgets Used 🧩

- MaterialApp
- Scaffold
- AppBar
- TextFormField
- ElevatedButton
- SnackBar
- Column
- Padding

---

# Form Example 💻

```dart
TextFormField(
  decoration: InputDecoration(
    labelText: "Name",
    border: OutlineInputBorder(),
  ),
)
```

---

# Submit Button Example 💻

```dart
ElevatedButton(
  onPressed: () {
    ScaffoldMessenger.of(context).showSnackBar(
      SnackBar(
        content: Text("Form Submitted"),
      ),
    );
  },
  child: Text("Submit"),
)
```

---

# Future Improvements 🔥

- Form validation
- Firebase integration
- Store user data
- Authentication system
- Responsive design
- Dark mode

---

# Author 👨‍💻

Created by Dev Pawar

---

# License 📄

This project is open-source and free to use.
