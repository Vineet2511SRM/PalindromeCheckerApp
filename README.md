# 🧩 Palindrome Checker Management System

<<<<<<< HEAD
A console-based Java application that validates whether a given string is a palindrome using different validation techniques across progressive use cases.

This project is designed to strengthen **core programming fundamentals**, **string manipulation**, and **algorithmic thinking**.

---

## 📌 Project Overview

The **Palindrome Checker Management System** demonstrates multiple approaches to palindrome validation through structured development stages (Use Cases).

Each use case introduces new concepts and techniques while building on previous learning.

Current implementation includes:

* **UC1 — Application Entry & System Initialization**
* **UC2 — Two-Pointer Character Comparison**
* **UC3 — Reverse String Comparison**

---

## 🚀 Use Case Details

---

### ✅ UC1 — Application Entry

**Goal:**
Initialize the system and display startup information.

**Concepts Used:**

* Class and `main()` method
* Program execution flow
* Console output formatting

**Sample Output**

=======
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

Welcome to the Palindrome Checker Management System
Version : 1.0
System initialized successfully

### ✅ UC2 — Hardcoded Palindrome Validation (Two-Pointer Method)

**Goal:**
Check whether a string is a palindrome by comparing characters from both ends.

**Logic:**

* Compare first and last characters
* Move inward toward center
* Stop early if mismatch found

**Key Concepts:**

* Two-pointer technique
* Loop optimization (`length / 2`)
* Boolean flag control
* Efficient comparison without extra memory

**Time Complexity:** O(n)

**Sample Output**

```
Input text: madam
Is it a Palindrome? : true
```

---

### ✅ UC3 — Reverse String Based Palindrome Check

**Goal:**
Check palindrome by reversing the string and comparing it with the original.

**Logic:**

* Iterate string in reverse order
* Build reversed string
* Compare using `equals()`

**Key Concepts:**

* For loop reverse traversal
* String immutability
* String concatenation
* Transformation-based validation

**Time Complexity:** O(n)
**Space Complexity:** O(n) (extra reversed string)

**Sample Output**

```
Input text: madam
Reversed text: madam
Is it a Palindrome? : true
```

---

## 🏗️ Comparison of Approaches

| Use Case | Method                    | Extra Space | Performance     | Concept Focus        |
| -------- | ------------------------- | ----------- | --------------- | -------------------- |
| UC1      | System initialization     | None        | —               | Program structure    |
| UC2      | Two-pointer comparison    | No          | Fastest         | Algorithm efficiency |
| UC3      | Reverse string comparison | Yes         | Slightly slower | String manipulation  |

---

## ▶️ How to Compile and Run

### Compile Java File
=======
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
>>>>>>> e60fdb380d9df47691ceaaef696ae5e0b7eff173

```bash
javac PalindromeCheckerApp.java
```

<<<<<<< HEAD
### Run Program
=======
### 3️⃣ Run the Program
>>>>>>> e60fdb380d9df47691ceaaef696ae5e0b7eff173

```bash
java PalindromeCheckerApp
```

---

## 🛠️ Technologies Used

<<<<<<< HEAD
* Java 17+
* Git
* GitHub

---

## 📚 Concepts Learned

* Program entry structure in Java
* String handling and immutability
* Loop control and optimization
* Algorithm design strategies
* Time and space trade-offs
* Multiple problem-solving approaches

---




## 🔮 Future Enhancements

* User input palindrome checking
* Case-insensitive comparison
* Ignore spaces and special characters
* StringBuilder optimization
* Menu-driven interface
* Performance benchmarking

---

## 👨‍💻 Author

**Vineet Seth**
GitHub: https://github.com/Vineet2511SRM

---
=======
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
>>>>>>> e60fdb380d9df47691ceaaef696ae5e0b7eff173
