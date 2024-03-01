## 10. Deadlock Handling Techniques

### 1. Deadlock Prevention: 
Deadlock prevention techniques aim to eliminate one
or more of the necessary conditions for deadlock to occur. These conditions
include mutual exclusion, hold and wait, no preemption, and circular wait. By
ensuring that one or more of these conditions are not satisfied, deadlocks
can be prevented from happening in the first place. However, prevention
techniques may impose restrictions on resource allocation and may not be
always feasible or efficient.

### 2. Deadlock Avoidance: 
Deadlock avoidance techniques use resource
allocation algorithms and resource request protocols to avoid situations that
may lead to deadlocks. These techniques involve the use of resource
allocation graphs, bankers' algorithm, or other dynamic allocation strategies.
The idea is to have a system that can predict whether granting a resource
request will lead to a potential deadlock. If a request might cause a deadlock,
it is delayed until granting it will not cause any issues.

### 3. Deadlock Detection: 
Deadlock detection techniques involve periodically
examining the resource allocation state to determine if a deadlock has
occurred. This can be achieved through algorithms such as the resourceallocation graph or the Banker's algorithm. When a deadlock is detected, the
system can take appropriate actions to resolve it, such as terminating
processes, resource preemption, or rolling back the system to a safe state.

### 4. Deadlock Recovery: 
Deadlock recovery techniques are used to recover
from a deadlock once it has been detected. This involves terminating one or more processes involved in the deadlock to break the circular wait and
release the resources held by those processes. The terminated processes
can be restarted later to continue their execution.

### 5. Deadlock Ignorance: 
Some systems choose to ignore the problem of
deadlocks entirely. This approach assumes that deadlocks will rarely occur
and focuses on other system aspects. However, it is generally not
recommended unless deadlocks are extremely rare or have minimal impact
on system functionality. Operating systems like Windows and Linux mainly
focus on performance. However, the performance of the system decreases if
it uses a deadlock handling mechanism all the time if a deadlock happens 1
out of 100 times then it is completely unnecessary to use the deadlock
handling mechanism all the time.
