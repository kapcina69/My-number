# My Number – Slagalica Game (Assembly Implementation)

This project is an assembly language implementation of the game **"My Number"** from the Serbian quiz show **"Slagalica"**.

## 📋 Game Description

In "My Number", the player is given **six randomly selected numbers**, usually a mix of small (1–10) and large values (10, 25, 50, 75, 100). The goal is to use basic arithmetic operations (**addition, subtraction, multiplication, division**) on these numbers to reach a **randomly generated three-digit target number**.

The rules are:
- Each given number can be used **only once**.
- Not all six numbers must be used.
- Only **valid mathematical operations** are allowed (e.g., no division by zero, no non-integer results if division is used).
- The goal is to get **as close as possible** to the target number, ideally reaching it exactly.

## 💻 Implementation Details

- Written entirely in **assembly language**.
- Random number generation simulates the drawing of numbers and the target.
- The program handles **user input and interaction via the keyboard**.
- Arithmetic operations can be selected and applied to the chosen numbers.
- The result is displayed after each operation, and the player can continue building toward the target number.

## 📄 Task Description

The full task requirements are provided in the `text` file included in this repository.

## 🚀 How to Run

This project is designed to be run in an x86 environment (e.g., DOSBox or similar emulator supporting assembly execution). Instructions for building and running the project can be found in the `build_instructions.txt` file (if included).

## 🎯 Objective

Practice low-level programming, arithmetic logic, and input/output handling in assembly by implementing a classic logic-based number puzzle game.

