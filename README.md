# Object-Oriented Programming (OOP) Concepts in Python

## 🧠 Project Overview

This project demonstrates the fundamental concepts of **Object-Oriented Programming (OOP)** in Python. It focuses on creating and using classes, inheritance, and object interaction through multiple real-world examples.

The notebook `oop_update.ipynb` includes simple yet powerful examples that explain how classes and objects work in Python and how inheritance helps to reuse and extend functionality.

---

## 🎯 Objective

* Understand the basics of **OOP principles** in Python.
* Demonstrate **class creation**, **inheritance**, and **object behavior**.
* Show how one class can access or override features of another.
* Provide clear examples suitable for beginners and intermediate learners.

---

## ⚙️ Technologies Used

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Concepts Covered:**

  * Class and Object
  * Inheritance (Single, Multiple)
  * Method Overriding
  * Encapsulation
  * Object Interaction

---

## 📘 Code Explanation

Below are the main sections and examples included in the notebook.

### 1. Single Inheritance Example

```python
#inheritence single class
class animal():
    def speak(self):
        print('The cows speak like humba!....')

class car(animal):
    def sound(self):
        print('The car sounds like pip pip!...')

h1 = car()
h1.sound()
h1.speak()
```

✅ **Explanation:**

* `animal` is the parent class with a method `speak()`.
* `car` inherits from `animal`, adding its own method `sound()`.
* Object `h1` can call both `sound()` and `speak()` — showing single inheritance.

---

### 2. Multi-Level or Multiple Inheritance Example

```python
class A:
    def displayA(self):
        print('This is class A')

class B(A):
    def displayB(self):
        print('This is class B')

class C(B):
    def displayC(self):
```
