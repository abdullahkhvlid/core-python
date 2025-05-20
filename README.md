# core-python
This Python project demonstrates the use of file handling, data structures, and string processing. It includes three mini-programs designed to handle real-world tasks.

---

## 1. Text File Analyzer

Reads a `.txt` file and generates key statistics:

- Counts the total number of lines and words
- Identifies the top 5 most frequent words (ignores case and punctuation)
- Outputs a summary report to `summary.txt`

---

## 2. Student Record Sorter

Handles a list of student records stored as dictionaries with fields: `"name"`, `"age"`, and `"score"`.

The sorting function:

- Sorts students by descending score
- Breaks ties with ascending age
- Further breaks ties alphabetically by name

Returns a clean, sorted list of student data.

---

## 3. Email Validator

A function `validate_email(email)` that checks if an email is valid by:

- Ensuring exactly one `@` symbol
- Checking there's at least one `.` after `@`
- Making sure the domain is at least 3 characters long

Raises a `ValueError` for invalid emails.  
Returns `True` for valid ones.

---
