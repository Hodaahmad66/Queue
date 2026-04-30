# Circular Queue Implementation in C

This program implements a circular queue (ring buffer) in C and demonstrates its usage by enqueuing characters from a modified user input string and then dequeuing them to display the result.

## Features

- Fixed-size circular queue with capacity of 20 characters
- Standard queue operations: `enqueue`, `dequeue`, `isEmpty`, `isFull`
- Handles overflow and underflow conditions with error messages
- Wraps around automatically when reaching the end of the buffer

## Queue Operations

| Function | Description |
|----------|-------------|
| `initQueue()` | Initializes the queue with default values |
| `isEmpty()` | Checks if the queue has no elements |
| `isFull()` | Checks if the queue has reached maximum capacity |
| `enqueue()` | Adds a character to the rear of the queue |
| `dequeue()` | Removes and returns a character from the front |

## How It Works

1. The user is prompted to enter their name
2. The string `"CE-ESY"` is appended to the entered name
3. Each character from the resulting string is added to the circular queue
4. All characters are dequeued and printed in sequence

## Requirements

- C compiler (GCC, Clang, or MSVC)
- Standard C libraries: `stdio.h`, `string.h`

## Compilation

```bash
gcc circular_queue.c -o circular_queue
