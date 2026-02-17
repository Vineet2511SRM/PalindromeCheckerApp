# 🧩 Palindrome Checker Management System

A console-based Java application that validates whether a given string is a palindrome using multiple validation techniques.

The project progressively introduces different approaches to strengthen **core programming fundamentals**, **string handling**, and **data structure understanding**.

---

## 📌 Project Objective

Design and implement a Java application that checks palindrome strings under different validation strategies while demonstrating algorithm efficiency and memory awareness.

---

## 🚀 Implemented Use Cases

---

### ✅ UC1 — Application Entry

Initializes the system and displays startup information.

**Concepts**

* Class structure
* `main()` method
* Program initialization

---

### ✅ UC2 — Two-Pointer String Comparison

Compares characters directly from both ends of the string.

**Flow**

* Compare start and end characters
* Move inward
* Stop on mismatch

**Data Structure:** String
**Time Complexity:** O(n)
**Extra Space:** None

---

### ✅ UC3 — Reverse String Comparison

Reverses the string and compares it with the original.

**Flow**

* Traverse string in reverse
* Build reversed string
* Compare using `equals()`

**Data Structure:** String
**Time Complexity:** O(n)
**Extra Space:** O(n)

---

### ✅ UC4 — Character Array Based Palindrome Check ⭐

**Goal**
Convert string to character array and compare characters using index-based access.

**Flow**

1. Convert string to `char[]`
2. Use two-pointer technique
3. Compare start and end characters
4. Stop on mismatch

**Key Concepts**

* Character Array (`char[]`)
* Array indexing
* Two-pointer technique
* Efficient comparison without extra object creation
* Time complexity awareness

**Data Structure:** `char[]`
**Time Complexity:** O(n)
**Extra Space:** Minimal (array representation)

---

## 🏗️ Approach Comparison

| Use Case | Method             | Extra Space | Performance | Concept Focus         |
| -------- | ------------------ | ----------- | ----------- | --------------------- |
| UC1      | Initialization     | None        | —           | Program structure     |
| UC2      | Two-pointer string | None        | Fast        | Direct comparison     |
| UC3      | Reverse string     | Yes         | Moderate    | String transformation |
| UC4      | Character array    | Minimal     | Efficient   | Memory & indexing     |

---

## 🖥️ Sample Output (UC4)

```
Input : radar
Is Palindrome? : true
```

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

## 🔮 Future Enhancements

* User input validation
* Case-insensitive comparison
* Ignore spaces and special characters
* StringBuilder optimization
* Menu-driven application
* Performance benchmarking

---

## 👨‍💻 Author

**Vineet Seth**
GitHub: https://github.com/Vineet2511SRM
