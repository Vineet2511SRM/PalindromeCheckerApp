# 🧩 Palindrome Checker Management System

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
* **UC4 — Character Array Based Validation**

---

## 🚀 Use Case Details

---

### ✅ UC1 — Application Entry

**Goal:**
Initialize the system and display startup information.

**Concepts Used**

* Class and `main()` method
* Program execution flow
* Console output formatting

**Sample Output**

```
Welcome to the Palindrome Checker Management System
Version : 1.0
System initialized successfully
--------------------------------------------------
```

---

### ✅ UC2 — Hardcoded Palindrome Validation (Two-Pointer Method)

**Goal:**
Check whether a string is a palindrome by comparing characters from both ends.

**Logic**

* Compare first and last characters
* Move inward toward center
* Stop early if mismatch found

**Key Concepts**

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

**Logic**

* Iterate string in reverse order
* Build reversed string
* Compare using `equals()`

**Key Concepts**

* For loop reverse traversal
* String immutability
* String concatenation
* Transformation-based validation

**Time Complexity:** O(n)
**Space Complexity:** O(n)

**Sample Output**

```
Input text: madam
Reversed text: madam
Is it a Palindrome? : true
```

---

### ✅ UC4 — Character Array Based Palindrome Check ⭐

**Goal:**
Convert string to character array and compare characters using index-based access.

**Flow**

1. Convert string to `char[]`
2. Use two-pointer technique
3. Compare start and end characters
4. Stop on mismatch

**Key Concepts**

* Character array (`char[]`)
* Array indexing
* Two-pointer technique
* Efficient comparison without creating extra objects
* Time complexity awareness

**Data Structure:** char[]
**Time Complexity:** O(n)
**Extra Space:** Minimal

**Sample Output**

```
Input : radar
Is Palindrome? : true
```

---

## 🏗️ Comparison of Approaches

| Use Case | Method                     | Extra Space | Performance | Concept Focus         |
| -------- | -------------------------- | ----------- | ----------- | --------------------- |
| UC1      | System initialization      | None        | —           | Program structure     |
| UC2      | Two-pointer comparison     | None        | Fastest     | Algorithm efficiency  |
| UC3      | Reverse string comparison  | Yes         | Moderate    | String transformation |
| UC4      | Character array comparison | Minimal     | Efficient   | Memory & indexing     |

---

## ▶️ How to Compile and Run

### Compile Java File

```bash
javac PalindromeCheckerApp.java
```

### Run Program

```bash
java PalindromeCheckerApp
```

---

## 🛠️ Technologies Used

* Java 17+
* Git
* GitHub

---

## 📚 Concepts Learned

* Program entry structure in Java
* String handling and immutability
* Loop control and optimization
* Array indexing and traversal
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
