# Introduction to Flask for Web Development
Flask is a lightweight web framework for Python.

## Creating a Simple Flask App:
You can create a basic web application using Flask.

Example:
from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return 'Hello, Flask!'

if __name__ == '__main__':
    app.run(debug=True)

