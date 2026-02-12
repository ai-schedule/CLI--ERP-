# 🎓 Mini ERP System (Console-Based Python Project)

A role-based Mini ERP (Enterprise Resource Planning) system built using basic Python concepts including:

- OOP (Class-Based Design)
- File Handling
- Role-Based Access Control
- Dictionary & Tuple Data Structures
- Loop & Menu-Driven Interface

---

## 🚀 Features

### 🔐 Authentication
- Account creation
- Strong password validation using Regex
- Login verification system
- Role-based access control

---

### 👨‍🏫 Admin Panel
Admin can:
- Add / Update marks for any student
- Add attendance for any student
- View student marks
- View student attendance
- Calculate student percentage
- View student details
- Logout

---

### 👨‍🎓 Student Panel
Student can:
- View their marks
- Calculate average
- Calculate percentage
- View attendance
- View personal details
- Logout

---

## 🛠 Technologies Used

- Python 3
- Regular Expressions (Regex)
- File Handling (Read/Write)
- OOP Concepts
- Dictionary & Tuple
- Match-Case (Pattern Matching)

---

## Note:
here I used differenet method and different functions to divide the whole porject in parts. we can also add the exact format of the username like in which format you want to take username from the user.
---
## 📂 Data Storage Format

Each user has a separate `.txt` file.

File structure:


---

## 📊 Data Structures Used

| Feature      | Structure Used |
|-------------|----------------|
| Marks       | Dictionary `{subject: marks}` |
| Attendance  | Tuple `(attended, total)` |
| Role        | String (`admin` / `student`) |

---

## 🔒 Role-Based Access Control

The system internally uses a `role` attribute:

- `admin` → Full control
- `student` → View-only access

Role is used for permission checks but not displayed in the UI.

---

## ▶️ How To Run

1. Open terminal
2. Navigate to project directory
3. Run:

```bash
python overall.py

