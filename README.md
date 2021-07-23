# Concurrency

1. Sequential programming refers to a set of ordered instructions executed one at a time on one CPU.
2. Concurrent programming handles several operations at one time and doesn’t require hardware support (using either one or multiple cores).
3. Parallel programming executes multiple operations at the same time on multiple CPUs. All parallel programs are concurrent, running simultaneously, but not all concurrency is parallel. The reason is that parallelism is achievable only on multicore devices.
3. Multitasking concurrently performs multiple threads from different processes. Multitasking doesn’t necessarily mean parallel execution, which is achieved only when using multiple CPUs.
4. Multithreading extends the idea of multitasking; it’s a form of concurrency that uses multiple, independent threads of execution from the same process. Each thread can run concurrently or in parallel, depending on the hardware support.




Links : 

I suppose closure is better solution than lock that's why : 
https://web.archive.org/web/20150707082707/http://diditwith.net/PermaLink,guid,235646ae-3476-4893-899d-105e4d48c25b.aspx

