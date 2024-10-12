# Web Development with Flask
Flask is a micro web framework for Python that is easy to get started with.

## Setting Up a Basic Flask App:
You can create a simple web app using Flask.

Example:
from flask import Flask
app = Flask(__name__)

@app.route('/')
def home():
    return Hello, Flask!

if __name__ == '__main__':
    app.run(debug=True)

