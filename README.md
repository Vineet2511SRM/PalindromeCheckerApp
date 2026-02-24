# 🧩 Palindrome Checker App
## Use Case 12 — Strategy Pattern for Palindrome Algorithms

### 📌 Objective
To demonstrate dynamic selection of palindrome algorithms using the Strategy Design Pattern.

---

## 📖 Description

This implementation introduces the Strategy Pattern.

It includes:

- A PalindromeStrategy interface
- A concrete StackStrategy implementation
- Runtime strategy injection in the main class

This design allows new palindrome algorithms to be added without modifying existing logic.

---

## 🔑 Key Concepts Used

- Interface
- Polymorphism
- Strategy Design Pattern
- Algorithm interchangeability
- Encapsulation

---

## ⚙️ Design Structure

PalindromeStrategy (Interface)
↓
StackStrategy (Concrete Implementation)
↓
PalindromeCheckerApp (Client)

---

## ⏱ Complexity (Stack Strategy)

Time Complexity: O(n)
Space Complexity: O(n)

---

## 🖥 Sample Output

Input : Level  
Is Palindrome? : true

---

## ▶️ Compile & Run

Compile:
javac App/src/PalindromeCheckerApp.java

Run:
java -cp App/src PalindromeCheckerApp

---

## 👨‍💻 Author
Vineet Seth