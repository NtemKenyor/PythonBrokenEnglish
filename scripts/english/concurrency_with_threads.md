# Concurrency with Threads
Threads allow you to run multiple tasks simultaneously.

## Using the threading Module:
You can create and manage threads in your Python applications.

Example:
import threading

def print_numbers():
    for i in range(5):
        print(i)

thread = threading.Thread(target=print_numbers)
thread.start()
thread.join()  # Wait for the thread to finish

