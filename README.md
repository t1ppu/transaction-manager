## 2238-CSE-5331- 002 
## DBMS MODELS AND IMPLEMENTATION (FALL 2023)
## A Simple Transaction Manager Implementation

This project involves implementing a transaction manager that handles concurrency control using the strict two-phase locking (S2PL) protocol with shared locks for read operations and exclusive locks for write operations. 
The transaction manager must manage locking, releasing objects, and ensuring transactions follow a correct schedule without deadlocks.
The project’s runtime environment consists of a main thread handling input, initializing data structures, and managing mutex and condition variables. 
The main thread creates a transaction manager object and a hash table acting as a lock table. As input is read, separate threads are created to carry out each transaction operation, allowing concurrent execution where possible.
