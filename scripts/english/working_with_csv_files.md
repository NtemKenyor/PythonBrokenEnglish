# Working with CSV Files
CSV (Comma-Separated Values) files are commonly used for data storage.

## Using the csv Module:
You can read from and write to CSV files using the built-in csv module.

Example:
import csv

# Writing to a CSV file
with open('data.csv', 'w', newline='') as csvfile:
    writer = csv.writer(csvfile)
    writer.writerow(['Name', 'Age'])
    writer.writerow(['Alice', 25])

# Reading from a CSV file
with open('data.csv', 'r') as csvfile:
    reader = csv.reader(csvfile)
    for row in reader:
        print(row)

