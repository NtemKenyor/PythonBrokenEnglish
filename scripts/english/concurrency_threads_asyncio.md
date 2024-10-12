# Concurrency: Threads and Asyncio
Concurrency allows your program to perform multiple tasks simultaneously.

## Using Threads:
You can create threads to run tasks in parallel.

Example:
import threading

def task():
    print('Task running!')

thread = threading.Thread(target=task)
thread.start()

