# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 
```
class saveetha:
    def add(self, a, b):
        return a + b
    def div(self, a, b):
        return a / b
a = int(input())
b = int(input())
obj = saveetha()
while True:
    choice = int(input())
    match choice:
        case 1:
            print("Result:", obj.add(a, b))
        case 2:
            print("Result:", obj.div(a, b))
        case 0:
            print("Exiting")
            break
        case _:
            print("invalid choice")
```
## Output Example
<img width="485" height="416" alt="image" src="https://github.com/user-attachments/assets/b777bd55-3681-48fc-bf1b-934ea1e2d5fe" />

##Result 
   Thus the Python program to perform addition and division using class and switch case has been executed successfully.
