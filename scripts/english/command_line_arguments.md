# Command-Line Arguments
You can pass arguments to your Python script from the command line.

## Using sys.argv:
You can access command-line arguments using the sys module.

Example:
import sys

if len(sys.argv) > 1:
    print('Arguments:', sys.argv[1:])  # Output: List of arguments

