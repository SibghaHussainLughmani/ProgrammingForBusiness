# Programming for Business
## Pointers & Dynamic Memory in C++
##  Overview
This repository contains solutions for **Lab 09: Pointers & Dynamic Memory in C++** as part of the *Programming for Business* course.
The lab focuses on understanding how memory works in C++ using:
- Pointers
- Dynamic memory allocation (`new` / `delete`)
- Dynamic arrays (`new[]` / `delete[]`)
- Pointer-based logic for real-world financial applications
All tasks are designed using fintech-inspired scenarios to simulate real business systems like banking, HR, and investment management.
##  Learning Objectives
- Understand pointer variables and memory addresses
- Use dynamic memory allocation in runtime applications
- Work with dynamic arrays for flexible data handling
- Apply pointer arithmetic and dereferencing
- Prevent memory leaks using proper deallocation
- Build real-world inspired financial systems in C++
##  Project Structure
ExpenseTracker
BalanceSwap
PayrollSystem
InvestmentCalculator
## Descriptions
## Daily Expense Tracker
A dynamic C++ program that allows users to input the number of days they want to track expenses. It allocates memory at runtime to store daily spending, calculates the total expenditure and average daily expense, and frees memory using `delete[]` after processing.
**Key Concepts:**
- Dynamic arrays
- Pointer-based storage
- Memory cleanup
## Dual-Account Balance Swap Engine
This program demonstrates pointer manipulation by swapping two bank account balances (savings and current) without using a third variable. The swap is performed entirely through pointers, simulating a financial rebalancing operation.
**Key Concepts:**
- Pointer referencing (`&`)
- Pointer dereferencing (`*`)
- In-place value swapping
## Payroll & Employee Records System
A dynamic employee management system that takes the number of employees at runtime and stores their names and salaries using dynamically allocated arrays. It identifies the highest-paid employee and displays all records in a formatted output.
**Key Concepts:**
- Dynamic arrays for strings and integers
- Struct-like data handling using pointers
- Searching algorithms (max salary)
- Memory deallocation
## Task 04 — Investment Portfolio Profit Calculator
A financial simulation program that calculates a 10% annual return on multiple investments. It uses pointer arithmetic and dynamic memory allocation to process investment data efficiently and displays profit for each entry.
**Key Concepts:**
- Pointer arithmetic
- Financial computation using arrays
- Runtime memory allocation
- Heap memory management
## Technologies Used
- C++
- Pointers
- Dynamic Memory Allocation
- Arrays
- Console Input/Output
## Key Concepts Practiced
- Memory addresses and pointer variables
- Heap vs stack memory
- `new` and `delete`
- `new[]` and `delete[]`
- Pointer dereferencing
- Safe memory management
##  How to Run
1. Open any C++ IDE (VS Code, Dev C++, Code::Blocks)
2. Open any `.cpp` file
3. Compile the program:
```bash
g++ filename.cpp -o output

---

## 🧩 Task Descriptions

---

## 📊 Task 01 — Daily Expense Tracker
A dynamic C++ program that allows users to input the number of days they want to track expenses. It allocates memory at runtime to store daily spending, calculates the total expenditure and average daily expense, and frees memory using `delete[]` after processing.

**Key Concepts:**
- Dynamic arrays
- Pointer-based storage
- Memory cleanup

---

## 💰 Task 02 — Dual-Account Balance Swap Engine
This program demonstrates pointer manipulation by swapping two bank account balances (savings and current) without using a third variable. The swap is performed entirely through pointers, simulating a financial rebalancing operation.

**Key Concepts:**
- Pointer referencing (`&`)
- Pointer dereferencing (`*`)
- In-place value swapping

---

## 👨‍💼 Task 03 — Payroll & Employee Records System
A dynamic employee management system that takes the number of employees at runtime and stores their names and salaries using dynamically allocated arrays. It identifies the highest-paid employee and displays all records in a formatted output.

**Key Concepts:**
- Dynamic arrays for strings and integers
- Struct-like data handling using pointers
- Searching algorithms (max salary)
- Memory deallocation

---

## 📈 Task 04 — Investment Portfolio Profit Calculator
A financial simulation program that calculates a 10% annual return on multiple investments. It uses pointer arithmetic and dynamic memory allocation to process investment data efficiently and displays profit for each entry.

**Key Concepts:**
- Pointer arithmetic
- Financial computation using arrays
- Runtime memory allocation
- Heap memory management

---

## 🛠️ Technologies Used
- C++
- Pointers
- Dynamic Memory Allocation
- Arrays
- Console Input/Output

---

## ⚠️ Key Concepts Practiced
- Memory addresses and pointer variables
- Heap vs stack memory
- `new` and `delete`
- `new[]` and `delete[]`
- Pointer dereferencing
- Safe memory management

---

## 🚀 How to Run

1. Open any C++ IDE (VS Code, Dev C++, Code::Blocks)
2. Open any `.cpp` file
3. Compile the program:

```bash
g++ filename.cpp -o output
Author
Course: Programming for Business
Lab: 09 — Pointers & Dynamic Memory
Student: Sibgha Hussain Lughmani
