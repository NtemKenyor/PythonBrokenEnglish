# Context Managers
Context managers allow you to manage resources efficiently, like files.

## Using the with Statement:
You can use the with statement to ensure proper acquisition and release of resources.

Example:
with open('example.txt', 'w') as file:
    file.write('This is a context manager example.')

