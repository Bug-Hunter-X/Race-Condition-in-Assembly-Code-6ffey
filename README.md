# Assembly Race Condition Example

This repository demonstrates a simple example of a race condition in assembly language.  The code attempts to increment a value in memory. However, without proper synchronization mechanisms, this operation is vulnerable to race conditions if accessed concurrently by multiple threads or processes.

The `bug.asm` file contains the flawed code exhibiting the race condition. The `bugSolution.asm` file provides a possible solution using atomic operations (if available in the target architecture) or other synchronization primitives to address the issue.

This example highlights the importance of careful memory management and synchronization when working with concurrent programming in assembly language.