# Inheritance and Polymorphism
Inheritance allows classes to inherit attributes and methods from other classes.

## Using Inheritance:
You can create a new class that inherits from an existing class.

Example:
class Animal:
    def speak(self):
        print('Animal speaks!')

class Cat(Animal):
    def speak(self):
        print('Meow!')

my_cat = Cat()
my_cat.speak()  # Output: Meow!

