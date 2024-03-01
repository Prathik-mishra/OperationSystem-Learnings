## 8. Process Synchronisation Mechanisms

Here are some of the mechanisms that fulfill the above process synchronization requirements:

### 1. Locks/Mutexes: 
Locks or mutexes (mutual exclusions) provide a simple and
effective way to achieve mutual exclusion. They allow only one process or
thread to acquire the lock at a time, ensuring exclusive access to a shared
resource or critical section. Locks can be implemented using hardware
instructions or software constructs.

### 2. Semaphores: 
Semaphores are synchronization objects that can be used to
control access to shared resources. They can be implemented as binary
semaphores (mutexes) or counting semaphores. Counting semaphores allow
a specified number of processes or threads to access a shared resource
simultaneously. Semaphores provide mechanisms for mutual exclusion,
signaling, and coordination.

### 3. Read-Write Locks: 
Read-write locks provide synchronization mechanisms
for scenarios where multiple readers can simultaneously access a shared
resource without conflicts, but exclusive access is required for writers. Read
locks can be acquired simultaneously by multiple readers, while write locks
are exclusive. Read-write locks allow for better concurrency when reading is
more frequent than writing.
