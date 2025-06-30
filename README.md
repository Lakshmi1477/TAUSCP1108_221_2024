# TAUSCP1108_221_2024

# 🎓 Student Report Card Management System

A console-based mini project developed in **C language** to automate the process of maintaining and managing academic records of students. This project is capable of calculating grades, computing SGPA, saving/loading student data, and searching records by roll number.

---

## 📌 Problem Statement

In educational institutions, managing student records manually is time-consuming and error-prone. Calculating grades and SGPA across multiple subjects often leads to inconsistencies. This project addresses these issues by providing a structured, efficient, and reusable system to manage academic records digitally.

---

## 🎯 Objectives

- ✅ Automate student academic record management
- ✅ Compute grades and SGPA based on marks and credit
- ✅ Store and retrieve records using file handling
- ✅ Support multiple students and subjects
- ✅ Enable search functionality using roll number
- ✅ Reinforce programming concepts such as:
  - Structures
  - Arrays
  - Functions
  - File I/O
  - Menu-driven programming

---

## ⚙️ Features

- 🎓 Input student data: name, roll number, subject-wise marks and credits
- 📊 Grade and SGPA calculation using a standard scale
- 💾 Save and load student records via text file
- 🔍 Search for student reports using roll number
- 🖥️ Console-based menu for easy user interaction

---

## 🧰 Tech Stack Used

| Component               | Technology                 |
|------------------------|----------------------------|
| Language               | C                          |
| Compiler               | Turbo C / GCC              |
| File Storage           | `.txt` file (plain text)   |
| Operating System       | Windows / Linux compatible |
| Interface              | Console (CLI)              |

---

## 📈 Methodology

1. **Problem Analysis**: Defined the need and expected output (grades, SGPA).
2. **System Design**:
   - Struct `Subject` for each subject's details
   - Struct `Student` to encapsulate a student's information
3. **Modular Functions**:
   - `calculateGrade()`, `inputStudent()`, `displayStudent()`, etc.
4. **Implementation**:
   - C functions with loops, structs, and file I/O
   - Menu-driven main program loop
5. **Testing**:
   - Validated grade logic, file reliability, edge cases
6. **Output**:
   - Printed subject-wise report and overall SGPA per student

---

## 📌 Outcomes

- Built a working report card system that supports:
  - Multiple students
  - Subject-based grading
  - Data persistence
- Learned modular C programming and file operations
- Demonstrated real-world use of `struct` and arrays

---

## 💡 Strategies for Code Optimization

- Broke code into reusable functions
- Used structs to model complex data
- Employed loops to avoid redundancy
- Applied simple file handling for persistence
- Designed clean, minimal menu-driven UI

---

## 🚀 Possible Improvements

- Replace static arrays with dynamic memory allocation
- Add input validation (e.g., mark range)
- Allow record updating/deletion
- Implement GPA ranking or summary statistics

---

## 👨‍💻 Author

**R. Lakshmi**  
B.Tech AIML-B | Roll No: 122411530221  
The Apollo University, Chittoor  
Academic Year: 2024–2025

---

## 📜 License

This project is for academic and educational purposes only. You are free to modify and expand upon it for learning use.

---
