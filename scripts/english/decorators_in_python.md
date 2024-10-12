# Decorators in Python
Decorators are a way to modify the behavior of functions or methods.

## Using a Simple Decorator:
You can create a decorator to wrap a function.

Example:
def my_decorator(func):
    def wrapper():
        print(Something is happening before the function is called.)
        func()
        print(Something is happening after the function is called.)
    return wrapper

@my_decorator
def say_hello():
    print(Hello!)

say_hello()

