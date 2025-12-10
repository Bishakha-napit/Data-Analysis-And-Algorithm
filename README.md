# Data Structures Implementation in C

This repository contains implementations of fundamental data structures in C programming language.

## Contents

### 1. Stack Implementation (`stack.c`)

A stack is a linear data structure that follows the LIFO (Last In, First Out) principle. The implementation includes:

- **Structure**: A stack with a fixed array size of 100 elements
- **Operations**:
  - `push(value)`: Adds an element to the top of the stack
  - `pop()`: Removes and returns the top element from the stack
  - `peek()`: Returns the top element without removing it
  - `isEmpty()`: Checks if the stack is empty
  - `isFull()`: Checks if the stack is full
- **Error Handling**: Stack overflow and underflow protection
- **Interactive Menu**: User-friendly command-line interface for testing all operations

### 2. Queue Implementation (`queue.c`)

A queue is a linear data structure that follows the FIFO (First In, First Out) principle. The implementation includes:

- **Structure**: A queue with a fixed array size of 5 elements
- **Operations**:
  - `enQueue(value)`: Adds an element to the rear of the queue
  - `deQueue()`: Removes and returns the front element from the queue
  - `display()`: Shows all elements in the queue
- **Error Handling**: Queue full and empty state management
- **Example Usage**: Demonstrates queue operations with sample data

## Compilation and Execution

To compile and run either program:

```bash
gcc -o stack stack.c
./stack

gcc -o queue queue.c
./queue
```

## Features

- Clean and well-commented code
- Error handling for edge cases
- User-friendly interfaces
- Modular functions for easy understanding
- Adherence to C programming best practices

## Learning Objectives

These implementations help understand:
- Basic principles of stack and queue data structures
- Array-based implementation of linear data structures
- Memory management in C
- Algorithm implementation in a systems programming language
