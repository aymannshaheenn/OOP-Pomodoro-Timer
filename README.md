# ⏳ Pomodoro++ — C++ OOP Console Productivity Suite

**Pomodoro++** is a console-based, object-oriented Pomodoro timer and productivity suite built in C++. Designed for students and professionals alike, this application goes beyond basic time management by integrating task tracking, daily goals, achievements, and schedules.

---

## 🌟 Features

### 🧑‍💻 User Authentication
- Sign up and log in with secure password hashing.
- Per-user data storage and personalization.

### 📋 Task Management
- Add tasks with priority (`HIGH`, `MED`, `LOW`), deadline, and required Pomodoro sessions.
- Edit, delete, and filter tasks by deadline or priority.
- Auto-suggests the most urgent task based on deadlines.

### ⏱️ Timer System
- Traditional Pomodoro (25/5) and Custom durations.
- Pause, resume, or complete a session early.
- Visual ASCII progress bar with countdown.
- End-of-session motivational quotes.

### 📈 Session History
- Automatically logs all completed sessions with timestamps.
- Tracks both work and break sessions.

### ⭐ Goal Tracking
- Set personal goals with active and achieved status.
- Visualize and update goal progress.
- Linked to XP and achievement system.

### 🏆 Achievements & XP System
- Earn XP for every completed session and achieved goal.
- Automatic rank upgrades: `Beginner` → `Intermediate` → `Advanced` → `Master`.

### 📅 Schedule & Daily Goals
- View active tasks sorted by deadline and priority.
- Set daily session completion goals.
- Track progress throughout the day.

### 🎨 UI & User Experience
- Clean and color-coded console interface.
- Motivational messages and session summaries.
- Error-handling and input validation.
- Supports ANSI escape codes (Windows CMD, Terminal, VS Code).

---

## 🛠️ Technologies Used

- **Language:** C++17
- **Paradigm:** Object-Oriented Programming (OOP)
- **Libraries:** Standard C++ Libraries (`<vector>`, `<fstream>`, `<chrono>`, `<thread>`, `<conio.h>`)
- **Storage:** File-based persistence (`users.txt`, `tasks_<username>.txt`, etc.)
- **UI:** Console-based, styled with ANSI color codes

---

## 🚀 How to Run

1. **Clone or Download** this repository.
2. **Open the project** in your C++ IDE (CodeBlocks, Visual Studio, or VS Code).
3. **Compile and Run** the `main()` function.
4. **Follow the menu interface** to create an account and begin managing your time efficiently.

### 📚 OOP Concepts Demonstrated
- Encapsulation (private members with public interfaces)

- Inheritance & Polymorphism (Timer, TraditionalTimer, CustomTimer)

- Composition (User has Tasks, Goals, History, Achievements)

- Abstraction (User doesn’t manage file I/O directly)

- Dynamic memory & File Handling

### ✅ Possible Future Improvements
- GUI version using Qt or SFML.

- Multi-user support with admin panel.

- Export data (CSV, JSON).

- Notification sounds with PlaySound.

### 🙋‍♀️ Author
Ayman Shaheen
Second Semester | BS Data Science
