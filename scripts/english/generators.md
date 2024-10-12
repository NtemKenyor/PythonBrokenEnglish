# Generators
Generators allow you to create iterators in a simple way using the yield statement.

## Creating a Generator:
You can define a generator function that yields values one at a time.

Example:
def countdown(num):
    while num > 0:
        yield num
        num -= 1

for value in countdown(5):
    print(value)  # Output: 5, 4, 3, 2, 1

