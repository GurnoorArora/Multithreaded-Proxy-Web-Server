# Multi-threading with Semaphores

This project implements multi-threading using Semaphores for synchronization instead of Condition Variables. Unlike `pthread_join()`, which requires passing a specific thread ID, Semaphore’s `sem_wait()` and `sem_post()` functions allow simpler thread management without needing parameters, making them a more efficient option for synchronization.

## Key OS Components Used:
- **Threading:** Multiple threads are utilized to execute tasks concurrently.
- **Locks:** Ensures thread safety by managing access to shared resources.
- **Semaphore:** Used for controlling access to critical sections without needing explicit thread identification.
- **Cache with LRU Algorithm:** Implements a Least Recently Used (LRU) cache to optimize memory access.

This project demonstrates efficient thread synchronization and resource management in a multi-threaded environment.
