# Multilevel Inheritance Example in Python

This Python project demonstrates the concept of **Multilevel Inheritance** to collect and display the **name**, **age**, and **location** of a person.

## 🎯 Aim

To write a Python program that uses multilevel inheritance to get and display a person’s name, age, and location.

## 🧠 Algorithm

1. **Parent Class**  
   - `__init__(name)` initializes the `name` attribute.  
   - `getName()` returns the `name`.

2. **Child Class (inherits Parent)**  
   - `__init__(name, age)` initializes `name` using `super()` and adds `age`.  
   - `getAge()` returns the `age`.

3. **Grandchild Class (inherits Child)**  
   - `__init__(name, age, location)` initializes `name` and `age` using `super()` and adds `location`.  
   - `getLocation()` returns the `location`.

4. **Input & Output**  
   - Take user input for name, age, and location.  
   - Create an instance of `Grandchild`.  
   - Print all details using class methods.

## Program
```
class Person:
    def set_name(self, name):
        self.name = name

class Age(Person):
    def set_age(self, age):
        self.age = age

class Location(Age):
    def set_location(self, location):
        self.location = location

    def display(self):
        print(self.name)


name = input()
age = int(input())
location = input()

obj = Location()
obj.set_name(name)
obj.set_age(age)
obj.set_location(location)

obj.display()
```
## Sample Output
<img width="570" height="240" alt="image" src="https://github.com/user-attachments/assets/1db51700-fcaf-492f-a205-e3104cbd3bf7" />

## Result 
Thus the Python program to get name, age, and location using multilevel inheritance and display the name has been executed successfully.
