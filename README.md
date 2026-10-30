# Python CLI Task & Expense Manager

Task & Expense Manager - a command-line application
===================================================
Needs Python 3.6 or newer. Uses only the standard library.
Data is saved automatically to tasks.json (Python's built-in json module).

How to run:
    python task_expense_manager.py                 (Windows: py task_expense_manager.py)
    python task_expense_manager.py mydata.json     use a different data file
    python task_expense_manager.py --selftest      check everything works on this computer

Type 'cancel' at any prompt to abort the current action.

OCR A-Level Computer Science (H446) concepts demonstrated
---------------------------------------------------------
Programming   modular design, decomposition, constants, dictionary dispatch,
              exception handling (incl. a custom exception), file handling,
              input validation (type, range, length, format, presence checks)
Algorithms    merge sort (recursive, divide and conquer, O(n log n)),
              binary search (O(log n)), linear search (O(n))
Data          lists, dictionaries, tuples, a stack (undo)
structures
OOP           classes, encapsulation (properties), inheritance, polymorphism,
              class methods
Data types    money stored as integer pence to avoid floating-point
              representation errors (0.1 + 0.2 != 0.3 in floating point)
