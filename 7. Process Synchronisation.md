## 7. Process synchronisation
Process synchronization is like a traffic signal that helps regulate the flow of
vehicles at an intersection. In the context of computing, it refers to techniques
and mechanisms used to coordinate the execution of processes or threads so
that they can work together harmoniously.
Imagine multiple processes or threads working on different tasks simultaneously.
Process synchronization ensures that they cooperate and communicate
effectively to avoid conflicts and ensure proper order of execution. It helps
prevent issues like race conditions, data inconsistencies, or deadlocks that can
arise when multiple processes or threads access shared resources
simultaneously.

Here are the key requirements of synchronization mechanisms:

### 1. Mutual Exclusion: 
The synchronization mechanism should enforce mutual
exclusion, which means that only one process or thread can access a shared
resource or enter a critical section at a time. It ensures that concurrent
access to shared resources does not result in conflicts or inconsistencies.
### 2. Progress:
The synchronization mechanism should allow processes or
threads to make progress by ensuring that at least one process/thread can
enter the critical section when it desires to do so. It avoids situations where
all processes/threads are blocked indefinitely, leading to a deadlock.
### 3. Bounded Waiting:
The synchronization mechanism should provide a
guarantee that a process/thread waiting to enter a critical section will
eventually be allowed to do so. It prevents a process/thread from being
starved or waiting indefinitely to access a shared resource
