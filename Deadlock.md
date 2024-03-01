## 9. Deadlock
A Deadlock is a situation where
each of the computer processes
waits for a resource that is being
assigned to another process. In
this situation, none of the
process gets executed since the
resource it needs, is held by
some other process that is also
waiting for some other resource
to be released.

Necessary Conditions for
Deadlocks:

### Mutual Exclusion: 
A resource can only be shared in a mutually exclusive manner. It implies thattwo processes cannot use the same resource at the same time.

### Hold and Wait:
A process waits for some resources while holding another resource at the
same time.

### No preemption: 
The process once scheduled will be executed till the completion. No other
process can be scheduled by the scheduler meanwhile.

### Circular Wait:
All the processes must be waiting for the resources in a cyclic manner so that
the last process is waiting for the resource which is being held by the first
process.
