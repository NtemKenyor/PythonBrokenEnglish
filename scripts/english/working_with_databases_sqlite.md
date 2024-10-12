# Working with Databases using SQLite
SQLite is a lightweight database engine included with Python.

## Connecting to SQLite:
You can connect to an SQLite database using the sqlite3 module.

Example:
import sqlite3

conn = sqlite3.connect('mydatabase.db')
cursor = conn.cursor()

