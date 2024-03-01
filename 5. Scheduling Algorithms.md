## 5. CPU scheduling Algorithms
CPU scheduling algorithms are used by the operating system to determine the
order in which processes are executed on the CPU.

### 1. First-Come, First-Served (FCFS):
In the FCFS scheduling algorithm, the process that arrives first is executed
first. It follows a non-preemptive approach, meaning that once a process
Operating System in One Video 5
starts running, it continues until it completes or voluntarily gives up the CPU.
FCFS is simple to understand but may lead to poor utilization of the CPU if
long processes arrive before shorter ones.

### 2. Shortest Job Next (SJN) or Shortest Job First (SJF):
SJN or SJF scheduling selects the process with the shortest total execution
time next. It can be either non-preemptive or preemptive. In the nonpreemptive variant, the process continues executing until it completes,
whereas in the preemptive variant, if a new process with a shorter burst time
arrives, the currently running process may be preempted. SJN/SJF aims to
minimize the average waiting time and is suitable when burst times are
known in advance.


### 3. Round Robin (RR):
Round Robin is a preemptive scheduling algorithm that assigns a fixed time
quantum (e.g., 10 milliseconds) to each process in a circular manner. Once a
process exhausts its time quantum, it is moved to the back of the ready
queue, allowing the next process in line to execute. RR provides fair
execution to all processes but may suffer from high context-switching
overhead and may not be efficient for long-running processes.

### 4. Priority Scheduling:
Priority scheduling assigns a priority value to each process, and the CPU is
allocated to the process with the highest priority. It can be either preemptive
or non-preemptive. In preemptive priority scheduling, if a higher-priority
process arrives, the currently running process may be preempted. In nonpreemptive priority scheduling, the process continues executing until it
completes or voluntarily gives up the CPU. Priority scheduling can suffer from
starvation if a lower-priority process never gets a chance to execute.

### 5. Multilevel Queue Scheduling:
Multilevel queue scheduling divides the ready queue into multiple priority
queues, each with its own scheduling algorithm. Processes are initially
placed in the highest-priority queue and can move between queues based on
predefined criteria. This approach allows for the differentiation of processes
based on their priority or characteristics, such as foreground or background
tasks. Each queue can use a different scheduling algorithm, such as FCFS,
SJF, or RR, suitable for the processes within that queue.





