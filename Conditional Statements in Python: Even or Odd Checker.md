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
```

a=int(input())
if a%2==1:
    if a>=25:
        print(f"{a} is an Odd number")
        print(f"{a} is greater than or equal to 25")
    else:
        print(f"{a} is an Odd number")
        print(f"{a} is lesser than 25")
else:
    print(f"{a} is NOT an Odd number")
```
## Output
<img width="1179" height="326" alt="image" src="https://github.com/user-attachments/assets/aed605c5-6d2c-4398-a8ca-60b5988fc98c" />

## Result
Thus program to check whether the given number is odd or not an odd using nested if..else. statements has been executed successfully.
