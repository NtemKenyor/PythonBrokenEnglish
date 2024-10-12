# Decorators
Decorators are a way to modify or enhance functions or methods.

## Creating a Simple Decorator:
You can use decorators to add functionality to existing functions.

Example:
def my_decorator(func):
    def wrapper():
        print('Something is happening before the function is called.')
        func()
        print('Something is happening after the function is called.')
    return wrapper

@my_decorator
def say_hello():
    print('Hello!')

say_hello()

