### 2. Process vs Threads vs Programs

### Program:
A program is a set of instructions written in a programming language that
performs a specific task or set of tasks. It is typically stored in a file on disk
and represents an executable entity. Programs can be compiled or
interpreted, and they serve as a blueprint for the execution of tasks on a
computer system.

### Process:
A process is an instance of a program in execution. When a program is
loaded into memory and executed, it becomes a process. A process is an
independent entity with its own memory space, resources, and execution
context. It has its own program counter, stack, and variables. Processes are
managed by the operating system, and each process runs in its own
protected memory space. Processes can be concurrent and communicate
with each other through inter-process communication mechanisms.

### Thread:
A thread is a unit of execution within a process. It represents a sequence of
instructions that can be scheduled and executed independently. Threads
share the same memory space and resources within a process. Multiple
threads within a process can run concurrently, allowing for parallel execution
of tasks. Threads within the same process can communicate and share data
more easily compared to inter-process communication. However, each
thread has its own program counter and stack.

In summary, a program is a set of instructions, a process is an instance of aprogram in execution with its own resources and memory space, and a thread is
a unit of execution within a process that allows for the concurrent execution of
tasks. Processes provide isolation and protection between different instances of a
program, while threads within a process share resource and enable parallel
execution of tasks.
