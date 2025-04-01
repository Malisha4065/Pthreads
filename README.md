# Pthreads Examples

This repository contains various examples demonstrating the use of POSIX threads (pthreads) in C. Each file showcases a different aspect of multithreading.

## File Descriptions

- `main.c` - Basic thread creation using `pthread_create`.
- `hello_arg1.c` - Passing arguments to threads using an array.
- `hello_arg2.c` - Passing multiple arguments to threads using a `struct`.
- `hello_arg3.c` - Demonstrates incorrect argument passing (race condition example).
- `join.c` - Using `pthread_join` to wait for threads to complete.
- `stack.c` - Managing thread stack size with `pthread_attr_setstacksize`.
- `dotprod_serial.c` - Serial implementation of dot product calculation.
- `dotprod_mutex.c` - Parallel dot product calculation using mutex for synchronization.
- `condvar.c` - Demonstrates condition variables for thread synchronization.

## How to Compile and Run

To compile any of the C files:
```bash
gcc -pthread -o <output_file> <source_file>.c
```

To run the compiled program:
```bash
./<output_file>
```