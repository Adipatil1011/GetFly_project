# 🎓 GetFly Student Portal App

**GetFly Student Portal** is a sleek and responsive Flutter application designed to manage student records efficiently. Created as part of the **GetFly Flutter Internship Project**, this app emphasizes clean UI/UX design, effective local data handling, and smooth navigation — everything a modern student database app should offer! 📚

---

## ✨ Key Features

- 🔹 **Add, update, and delete** student profiles  
- 🔹 User-friendly **form validation** with all required fields  
- 🔹 Clean and colorful **responsive UI**, built using a red-centric theme  
- 🔹 Works **offline** with temporary in-memory storage (upgradeable to Hive/SharedPreferences)  
- 🔹 Simple and intuitive **screen navigation**  
- 🔹 **Reusable widgets** and modular structure for scalability  

---

## 🧰 Tech Stack

- **Framework:** Flutter  
- **UI Design:** Material Design components  
- **State Management:** Basic `setState()` — ideal for local state updates  
- **Storage:** In-memory (can be easily integrated with Hive or SharedPreferences for persistent storage)

---

## 🔄 State Management Approach

- Utilized Flutter's native `setState()` for handling component-level state.  
- Ideal for smaller apps or screen-specific updates.  
- No need for global state solutions like Provider or Riverpod in this phase.  
- Can be scaled to use advanced state management if the app grows in complexity.

---

## 📝 Student Information Structure

Each student entry contains the following fields:

| Field           | Type            |
|------------------|-------------------|
| `id`             | Integer           |
| `name`           | String            |
| `email`          | String            |
| `date_of_birth`  | String (Date)     |
| `contact`        | String            |
| `department`     | String            |
| `year`           | String            |
| `address`        | String            |

---

## 🗂️ Project Structure
lib/
├── main.dart # App entry point
├── home_page.dart # Home screen listing students
├── add_student.dart # Add/Edit student form screen
├── student_card.dart # Reusable widget to display student info
├── models/
│ └── student.dart # Student data model
└── utils/
└── form_validators.dart # Input validation logic
