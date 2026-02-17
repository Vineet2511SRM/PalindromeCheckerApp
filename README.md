# 🧩 Palindrome Checker Management System

🚀 **Use Case 2: Hardcoded Palindrome Validation**

---

## 📌 Project Overview

The **Palindrome Checker Management System** is a console-based Java application that validates whether a given string is a palindrome.

This project focuses on strengthening **core programming fundamentals** and **basic data structure logic**.

The repository is updated to **Version 2.0**, which includes the following milestones:

✅ **UC1 — Application Entry**
Establishes the main entry point and system initialization messages.

✅ **UC2 — Palindrome Logic**
Implements an optimized character comparison algorithm using the **two-pointer approach**.

---

## 🏗️ Implementation Details

### 🔹 Key Concepts Used in UC2

* **Class & Main Method** — Entry point for JVM execution
* **String Literals** — Using predefined input from the String constant pool
* **Two-Pointer Technique** — Compare characters from both ends
* **Loop Optimization** — Iterate only up to `input.length() / 2`

---

## 🔄 Logic Flow

1. Program starts and displays system welcome messages.
2. A hardcoded string (example: `"madam"`) is initialized.
3. A loop compares characters at:

    * index `i`
    * index `length - 1 - i`
4. If mismatch occurs → `isPalindrome = false` and loop stops.
5. Final result is displayed in the console.

---

## 🖥️ Program Output

### ✅ UC1 — Application Entry

```
Welcome to the Palindrome Checker Management System
Version : 1.0
System initialized successfully
```

### ✅ UC2 — Hardcoded Palindrome Validation

```
Input text: madam
Is it a Palindrome? : true
```

### ✅ Combined Execution Output (UC1 + UC2)

```
Welcome to the Palindrome Checker Management System
Version : 2.0
System initialized successfully
--------------------------------------------------
Input text: madam
Is it a Palindrome? : true
```

---

## ▶️ How to Compile and Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Vineet2511SRM/PalindromeCheckerApp.git
cd PalindromeCheckerApp
```

### 2️⃣ Compile the Program

```bash
javac PalindromeCheckerApp.java
```

### 3️⃣ Run the Program

```bash
java PalindromeCheckerApp
```

---

## 🛠️ Technologies Used

* **Language:** Java 17+
* **Version Control:** Git & GitHub

---

## 📚 Git Commands Practiced

```bash
git status
git add PalindromeCheckerApp.java
git commit -m "Update UC2: Implement hardcoded palindrome validation logic"
git push origin main
```

---

## 👨‍💻 Author

**Vineet Seth**
GitHub: https://github.com/Vineet2511SRM
