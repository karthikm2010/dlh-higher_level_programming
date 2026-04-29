# Python Exceptions – AI Academy (DLH)

This repository contains my exercises covering Python exception handling and advanced error management as part of the AI Academy course at DLH. It focuses on writing robust programs that handle runtime errors gracefully.

## 📘 Objective

To build a strong understanding of exception handling in Python by learning:

- Safe execution of code
- Error handling using try/except/finally
- Raising exceptions manually
- Working with stderr
- Writing resilient and fault-tolerant programs

## 🧩 Topics Covered

### 🛡️ Exception Handling Basics

- `0-safe_print_list.py` – Safely print elements from a list
- `1-safe_print_integer.py` – Safely print integers
- `2-safe_print_list_integers.py` – Print only integers from a list

### ⚙️ Try / Except / Finally

- `3-safe_print_division.py` – Safe division with debug output
- `4-list_division.py` – Divide two lists element by element safely

### 🚨 Raising Exceptions

- `5-raise_exception.py` – Raise a TypeError
- `6-raise_exception_msg.py` – Raise a NameError with a message

### ⭐ Advanced

- `100-safe_print_integer_err.py` – Print integer with error to stderr
- `101-safe_function.py` – Execute a function safely
- `102-magic_calculation.py` – Recreate logic from Python bytecode

## ⚙️ Key Concepts Used

- `try / except / finally`
- exception handling
- `TypeError`, `ValueError`, `ZeroDivisionError`, `IndexError`
- `raise`
- stderr handling (`__import__('sys').stderr`)
- function pointers
- safe execution patterns

## 🎯 Learning Outcome

By completing this module, I am able to:

- Handle runtime errors effectively
- Write safe and robust Python code
- Use try/except/finally correctly
- Raise and manage custom exceptions
- Work with stderr for error reporting
- Understand and translate Python bytecode logic