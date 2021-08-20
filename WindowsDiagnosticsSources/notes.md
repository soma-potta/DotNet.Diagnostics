## Overview

Diagnostic helpers - Tracers, Debuggers and others. These fall into others category.

#### Process monitoring:

Process and threads have their own ids, a process can have multiple threads.  

Process characteristics:
- virtual memory - allocated by OS, not shared with other processes unless with special permissions
- System and user CPU time
- private memory
- I/O

### Tools for process monitoring:

#### Windows
-  Task manager etc
- A very good tool - Process hacker
- Process explorer

Process hacker can show all the threads and their call stack (when symbols are configured) within a process. Memory dump can also be taken.

#### Linux:
- procps
- pidstat
- htop

The above tools get data from /proc filesystem. File descriptor is a reference to a process in linux.

#### Tracing tools other than ETW/perf:
- Process Monitor (Windows) available from sysinternals
- strace (Linux)






