# 🧩 Palindrome Checker App
## Use Case 13 — Performance Comparison (Professional Version)

### 📌 Objective
To compare execution time of different palindrome validation algorithms.

---

## 📖 Description

This implementation benchmarks multiple algorithms:

1. Two Pointer Method
2. Stack Based Method
3. Recursive Method

Execution time is measured using:

System.nanoTime()

Each algorithm is executed separately and total execution duration is displayed.

---

## 🔑 Key Concepts Used

- System.nanoTime()
- Algorithm benchmarking
- Performance comparison
- Time complexity awareness
- Recursion vs Iteration

---

## ⚙️ Algorithms Compared

| Algorithm     | Time Complexity | Space Complexity |
|--------------|----------------|-----------------|
| Two Pointer  | O(n)           | O(1)            |
| Stack        | O(n)           | O(n)            |
| Recursive    | O(n)           | O(n) (call stack)|

---

## 🖥 Sample Output

Input : Level

Is Palindrome? : true

Execution Time Comparison:
Two Pointer : 84000 ns
Stack       : 126000 ns
Recursive   : 91000 ns

(Note: Execution time varies each run)

---

## ▶️ Compile & Run

Compile:
javac PalindromeCheckerApp.java

Run:
java PalindromeCheckerApp

---

## 👨‍💻 Author
Vineet Seth