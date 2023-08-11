# Atomic Hashtable
An implementation of atomic hash table.


## What is atomic hashtable?

Atomic hash is a type of hash table that is designed to be thread-safe. This means that multiple threads can access the hash table at the same time without causing any conflicts. Atomic hash tables are often used in concurrent programming applications where multiple threads need to access the same data.

Atomic hash tables work by using a technique called optimistic concurrency control. This technique allows multiple threads to read and write to the hash table without locking it. When a thread wants to read or write to the hash table, it first checks to see if the hash table has been modified by another thread since it last accessed it. If the hash table has not been modified, the thread can proceed with its operation. If the hash table has been modified, the thread will back off and try again later.
