# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```python
a = int(input("Enter a number: "))
if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```

## Output
<img width="1907" height="1013" alt="image" src="https://github.com/user-attachments/assets/3493b9ad-b949-43e0-a61b-f241d92fa60b" />


## Result
This program effectively distinguishes even and odd numbers using a simple conditional check and prints the correct label accordingly.
