# File Handling in Python
Python allows you to interact with files easily.

## Opening and Reading Files:
To read a file, you use the open() function.

Example:
with open('my_file.txt', 'r') as file:
    content = file.read()
    print(content)

## Writing to Files:
You can also write to a file using the 'w' mode.

Example:
with open('my_file.txt', 'w') as file:
    file.write(Hello, World!)

