# Data Serialization with JSON
JSON (JavaScript Object Notation) is a lightweight data interchange format.

## Using the json Module:
You can easily convert Python objects to JSON format.

Example:
import json

data = {name: Alice, age: 25}
json_string = json.dumps(data)
print(json_string)  # Output: {name: Alice, age: 25}

