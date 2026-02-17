# 🧩 Palindrome Checker Management System

A console-based Java application that validates whether a given string is a palindrome using different validation techniques across progressive use cases.

This project strengthens **core programming fundamentals**, **data structure usage**, and **algorithm design thinking**.

---

## 📌 Project Objective

Design and implement a Java application that checks palindrome strings under multiple validation strategies while demonstrating algorithm efficiency and data structure usage.

---

## 🚀 Implemented Use Cases

### ✅ UC1 — Application Entry

Program initialization and execution structure.

### ✅ UC2 — Two-Pointer String Comparison

Direct comparison from both ends of string.

### ✅ UC3 — Reverse String Comparison

Reverse string and compare with original.

### ✅ UC4 — Character Array Based Validation

Convert string to `char[]` and compare using index-based access.

### ✅ UC5 — Stack Based Palindrome Checker ⭐

**Goal**
Use stack to reverse characters and validate palindrome.

**Flow**

1. Push characters into stack
2. Pop characters in reverse order
3. Compare with original string
4. Print result

**Key Concepts**

* Stack (LIFO structure)
* Push operation
* Pop operation
* Natural reversal behavior
* Data structure driven validation

**Data Structure:** Stack
**Time Complexity:** O(n)
**Space Complexity:** O(n)

**Sample Output**

```
Input : noon
Is Palindrome? : true
```

---

## 🏗️ Approach Comparison

| Use Case | Method          | Extra Space | Concept Focus           |
| -------- | --------------- | ----------- | ----------------------- |
| UC2      | Two-pointer     | None        | Efficient comparison    |
| UC3      | Reverse string  | O(n)        | Transformation          |
| UC4      | Character array | Minimal     | Index-based access      |
| UC5      | Stack           | O(n)        | Data structure reversal |

---

## ▶️ How to Compile and Run

### Compile

```bash
javac PalindromeCheckerApp.java
```

### Run

```bash
java PalindromeCheckerApp
```

---

## 🛠️ Technologies Used

* Java 17+
* Git & GitHub

---

## 👨‍💻 Author

Vineet Seth
GitHub: https://github.com/Vineet2511SRM
