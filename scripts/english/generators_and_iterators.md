# Generators and Iterators
Generators are a simple way to create iterators in Python.

## Using Yield:
You can define a generator function using the yield statement.

Example:
def countdown(num):
    while num > 0:
        yield num
        num -= 1

for count in countdown(5):
    print(count)

