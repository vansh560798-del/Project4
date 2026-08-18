# Project 4
## 📌 Project Overview

**Project-4** is a C language project focused on basic **string manipulation and character processing**. The project contains programs that demonstrate how strings can be processed using loops, arrays, and conditional statements without relying on built-in string manipulation functions.

## 🎯 Objectives

* Understand string handling in C.
* Practice using character arrays.
* Use loops and conditional statements for string processing.
* Implement string operations without built-in string functions.
* Develop basic problem-solving and programming logic.

## 📂 Project Structure

```text
Project4
│
├── Q1.c    # Palindrome Checker
├── Q2.c    # Frequency Counter
└── README.md
```


### Q1 – Palindrome Checker

This program checks whether a given string is a **palindrome** or not.

A palindrome is a string that reads the same from both directions.

**Example:**

```text
Input:
nayan

Output:
The given string is a Palindrome.
```

**Concepts Used:**

* Character arrays
* `while` loop
* `for` loop
* Conditional statements
* Character comparison

The string length is calculated manually, without using functions such as `strlen()`.

### 🧩 Question-1 Included

####Code-->Q1

<img width="1440" height="900" alt="Untitled" src="https://github.com/user-attachments/assets/e958ac9d-5146-455d-88ca-8501a37d98d3" />

**Result**

<img width="1440" height="900" alt="Untitled 2" src="https://github.com/user-attachments/assets/066b941e-6fb5-40f3-b284-ad746e31a8ce" />


---

### Q2 – Frequency Counter

This program counts the number of times each character appears in a given string.

**Example:**

```text
Input:
development

Output:
Frequency of each letter:
d => 1
e => 3
v => 1
l => 1
o => 1
p => 1
m => 1
n => 1
t => 1
```

**Concepts Used:**

* Character arrays
* Nested `for` loops
* Conditional statements
* Character comparison
* Counting and tracking duplicate characters

## 🧩 Question-2 Included

**Code-->Q2**

<img width="1440" height="900" alt="Untitled 3" src="https://github.com/user-attachments/assets/a423be3f-1856-48ac-87b2-523e2fbaf89b" />


**Result**

<img width="1440" height="900" alt="Untitled 4" src="https://github.com/user-attachments/assets/23b55fb0-80cc-43ef-8027-cc0ef310ed4f" />


## 🛠️ Technologies Used

* **Language:** C
* **Compiler:** GCC / Any standard C compiler
* **Platform:** Windows / macOS / Linux

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone Project4
```

### 2. Open the project folder

```bash
cd Project4
```

### 3. Compile Q1

```bash
gcc Q1-Palindrome Checker.c
```

### 4. Run Q1

```bash
./a.exe
```

### 5. Compile Q2

```bash
gcc Q2-Frequency Counter.c
```

### 6. Run Q2

```bash
./a.exe
```

> On Mac,Linux(also works with windows) use `g++ Q1.c | g++ Q2.c`to run the compiled programs.
> On Mac,Linux(also works with windows) use `./a.out`to run the compiled programs.

## 📚 Learning Outcomes

After completing this project, the following concepts are demonstrated:

* Basic C programming
* String and character-array handling
* Loops and nested loops
* Conditional statements
* Manual string-length calculation
* Character frequency counting
* Basic algorithmic problem solving

## ⚠️ Assumptions

* The programs accept a single word as input.
* Input is handled as a character array.
* The palindrome checker is case-sensitive.
* Spaces and special multi-word input are not considered.

## 👨‍💻 Project Information

**Project Name:** PR. 6 Filament
**Language:** C
**Total Questions:** 2
**Project Type:** C Language Practical Project

---

## 📄 Conclusion

The Filament project demonstrates fundamental string-processing techniques in C using basic programming concepts such as arrays, loops, and conditional statements. The programs are designed to strengthen logical thinking and provide practical understanding of character and string manipulation in C.

**Made for C Language Practical Assignment.**
