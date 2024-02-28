## 3. Difference between Multiprogramming, Multiprocess, Multitasking, and Multithreading

### 1. Multiprocess:
Multiprocess refers to the execution of multiple processes on a system with
multiple CPUs or CPU cores. Each process is an instance of a running
program, and multiple processes can execute concurrently. In multiprocess
systems, each process has its own memory space and resources.
Multiprocessing aims to increase system throughput and provide faster
execution by distributing the workload across multiple processors.

### 2. Multithreading:
Multithreading involves executing multiple threads within a single process. A
thread is a lightweight unit of execution that can run concurrently with other
threads within the same process. Threads share the same memory space
and resources, such as file handles and network connections. Multithreading
allows for parallel execution within a process, enabling better utilization of
system resources and potentially improving performance by dividing tasks
into smaller units of work that can be executed concurrently.

### 3. Multiprogramming:
Multiprogramming is a technique where multiple programs are loaded intomemory simultaneously, and the CPU switches between them to execute
instructions. The purpose of multiprogramming is to maximize CPU utilization
and keep the CPU busy by quickly switching between different programs
when one is waiting for I/O or other operations. Each program has its own
separate memory space.

### 4. Multitasking:
Multitasking is a technique that allows multiple tasks or processes to run
concurrently on a single CPU. The CPU time is divided among the tasks,
giving the illusion of parallel execution. The operating system switches
between tasks rapidly, giving each task a time slice or quantum to execute.
Multitasking is commonly used in modern operating systems to provide
responsiveness and the ability to run multiple applications simultaneously.
