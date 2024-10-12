# Object-Oriented Programming (OOP)
OOP is a programming paradigm based on the concept of objects.

## Defining Classes and Objects:
You can define classes to create objects with properties and methods.

Example:
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        return f'{self.name} says Woof!'

my_dog = Dog('Buddy')
print(my_dog.bark())  # Output: Buddy says Woof!

