# Testing and Debugging
Testing and debugging are essential for building robust applications.

## Using unittest:
You can use the unittest module for writing test cases.

Example:
import unittest

def add(a, b):
    return a + b

class TestMathFunctions(unittest.TestCase):
    def test_add(self):
        self.assertEqual(add(2, 3), 5)

if __name__ == '__main__':
    unittest.main()

