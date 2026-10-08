# Python Functions

A structured collection of foundational Python programming exercises demonstrating core algorithms, mathematical operations, text parsing, and string manipulation techniques.

---

## 📌 Project Overview

This repository contains solutions to foundational programming challenges implemented in a Jupyter Notebook. The exercises cover control flow, basic data structures (lists, dictionaries), modular function design, and standard library modules.


1. Prime Number CheckerObjective: Determine whether an input natural number greater than 1 is a prime number.
     Approach: Checks divisors from 2 up to $\lfloor\sqrt{n}\rfloor$ to achieve $O(\sqrt{n})$ time complexity. Numbers less than or equal to 1 are eliminated immediately.
2. Random Number Product QuizObjective: Generate two pseudo-random integers and validate the user's multiplication answer interactively.
   Approach: Utilizes the random.randint module to select numbers between 1 and 10, compares the calculated product against user input, and returns validation feedback.
3. Squares of Even NumbersObjective: Calculate and display the squares of all even integers in the range $[100, 200]$.
   Approach: Iterates through the range using range(100, 201), applies modulo check (num % 2 == 0), and computes squares using exponentiation (**2).
4. Word Frequency CounterObjective: Parse a given string of text and count the number of occurrences of each word.
   Approach: Tokenizes string inputs via .split() and aggregates counts into a Python dictionary using .get().
5. Palindrome ValidatorObjective: Verify whether a given string reads the same backward as forward.
   Approach: Normalizes the text by casting to lowercase and stripping punctuation/whitespace using .isalnum(), then evaluates symmetry via string slicing (s ==   s[::-1]). 

---

## 📁 Repository Structure

```text
├── Basics_of_python.ipynb   # Jupyter Notebook containing code implementations & test runs
└── README.md                # Project documentation and exercise breakdowns


