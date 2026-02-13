# Debugging Challenge

## Instructions

You have TWO debugging tasks. Run each file and use the error messages to find and fix the bugs.

### Task 1: Code Errors (task1.py)
Run the file to see the first error. Fix it, run again, fix the next error, and repeat until the program runs completely.

**23 snippets to fix.**

### Task 2: Gas Station Receipt (task2.py)
This program generates a receipt but has input and data conversion bugs.

**Steps:**
1. Run the file - fix any errors in the `main()` function first
2. Once input works, comment out `main()` to use predefined test values
3. Continue fixing remaining bugs without having to enter input each time
4. Run pytest when done

---

## Testing Your Fixes

Run pytest to check your work:
```
pytest test_tasks.py -v
```

---



**TIPS:**
- Task 1: Look for typos, missing quotes, mismatched quotes, indentation issues, missing colons
- Task 2: Remember `input()` always returns a string - use `int()` or `float()` to convert before math
