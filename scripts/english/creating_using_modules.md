# Creating and Using Modules
Modules allow you to organize your code into reusable components.

## Creating a Module:
You can create a Python file with functions and import it in other scripts.

Example:
# mymodule.py
def greet(name):
    return f'Hello, {name}!'

# main.py
from mymodule import greet
print(greet('Alice'))

