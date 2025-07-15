# 📝 Online Examination System – Java Console Application

## 📌 Overview  
This is a **Java-based Online Examination System** developed as part of the **Oasis Infobyte Internship – Task 3**. The system allows users to log in, start a multiple-choice quiz, track their score, and even manage their profile. It simulates a real-time exam environment with a countdown timer and pass/fail result.

---

## 🛠️ Features

👤 **User Login**  
Prompt-based login with username, password, and full name.

🧠 **Start Exam**  
A quiz with multiple-choice questions and a countdown timer (30 minutes simulated).

📊 **Result Evaluation**  
Displays score, percentage, and pass/fail status after submission.

🔄 **Update Profile**  
Allows the user to update their full name.

🔐 **Change Password**  
Enables password change with current password verification.

🚪 **Logout**  
Gracefully logs the user out of the system.

---

## 🧑‍💻 Tech Stack

- **Language:** Java  
- **IDE:** IntelliJ IDEA / Eclipse  
- **Core Concepts:**  
  - Classes and Objects  
  - ArrayList  
  - Scanner for user input  
  - Timers for countdown  
  - Encapsulation and data management

---

## 🧾 How It Works

### 1. Login Screen
- Prompts for username, password, and full name.
- Initializes a `User` object and loads the main menu.

### 2. Main Menu Options
- Start Exam
- Update Profile
- Change Password
- Logout


### 3. Exam Flow
- 15 multiple-choice questions.
- A 30-minute countdown timer (simulated using `Timer` class).
- User inputs the answer for each question.
- Answers are stored and submitted at the end or when the time runs out.

### 4. Result Calculation
- Score is calculated by comparing user-selected answers with correct answers.
- Displays:
  - Total score
  - Percentage
  - Pass/Fail (40% is passing criteria)

### 5. Profile Update
- Allows the user to update their full name.

### 6. Password Change
- Old password verification before setting a new one.

### 7. Logout
- Ends session and displays a farewell message with the user's name.

---

## 📦 How to Run

1. Clone or download the repository.
2. Open the project in your preferred Java IDE (Eclipse/IntelliJ).
3. Compile and run `OnlineExamination.java`.
4. Follow on-screen instructions.

---

## 🙋‍♂️ Author

**Nitish Kumar Mishra**  
Java Developer Intern – Oasis Infobyte  
GitHub : github.com/Mishra-Nitish
LinkedIn : linkedin.com/in/mishra-nitish
