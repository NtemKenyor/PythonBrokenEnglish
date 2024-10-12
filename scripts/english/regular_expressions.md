# Regular Expressions in Python
Regular expressions (regex) are powerful tools for matching patterns in text.

## Using the re Module:
You can use Python's built-in re module for regex operations.

Example:
import re

pattern = r'\d+'  # Matches one or more digits
text = 'There are 123 apples.'
matches = re.findall(pattern, text)
print(matches)  # Output: ['123']

