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
class Person: 

   def init(self, name): 

      self.name = name

class Age(Person): 

   def init(self, name, age): 

      super().init(name) 

      self.age = age

class ID(Age): 

   def init(self, name, age, place): 

      super().init(name, age) 

      self.place = place

def display(self):
    
    print(self.name, self.age, self.place)

name = input() 

age = input() 

place = input()

person = ID(name, age, place)

person.display()

## Sample Output
<img width="716" height="227" alt="image" src="https://github.com/user-attachments/assets/4c147eea-0a55-40e1-bfbc-0599c0f239d8" />

## Result
Thus, To write a Python program that uses multilevel inheritance to get and display a person’s name, age, and location is verified.
