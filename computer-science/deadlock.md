- Today I learned that I forgot all the details of OS course I took a year ago.
- Today I recalled that there's 4 necessary conditions called `Coffman Conditions`
    that can potentially cause deadlocks in concurrent systems.

    1. Mutual exclusion: At least one resource must be held in a non-shareable 
        mode.
    2. Hold and wait: A process holding at least one resource and requesting
        additional resources which are held by other processes.
    3. No preemption: A resource can be released only volutarily by the process
        holding it.
    4. Circular wait: A process must be wating for a resource which is being
        held by another process, which in turn is waiting for the first process
        to release the resource.
