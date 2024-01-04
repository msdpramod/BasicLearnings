THREADS
-  Introduction of Multithreading: (Covered in this Video)
    * Definition of Multithreading
    * Benefits and Challenges of Multithreading
    * Processes v/s Threads
    * Multithreading in Java

-  Java Memory Model of Process and thread (Covered in this Video)

-  Basics of Threads - Part1:
    * Creating Threads
        * Extending the Thread Class
        * Implementing the Runnable Interface
    * Thread Lifecycle
        * New
        * Runnable
        * Blocked
        * Waiting
        * Timed Waiting
        * Terminated

-  Basics of Thread - Part2 : Inter Thread Communication and Synchronization
* Synchronization and Thread Safety
  * Synchronized Methods
  * Synchronized Blocks
* Inter-Thread Communication
  * wait(), notify(), and notifyAll() methods
  * Producer-Consumer Problem - Assingment


- Basics of Threads - Part3
    * Producer-Consumer Problem - Solution discuss
    * Stop, Resume, Suspended method is deprecated, understand why and its solution
    * Thread Joining
    * Volatile Keyword
    * Thread Priority and Daemon Threads

-  Some Advanced Topics
    * Thread Pools
        * Executor Framework
        * ThreadPoolExecutor
    * Callable and Future
    * Fork/Join Framework
    * ThreadLocal in Multithreading

-  Concurrency Utilities
    * java.util.concurrent Package
    * Executors and ExecutorService
    * Callable and Future
    * CompletableFuture
    * ScheduledExecutorService
    * CountDownLatch, CyclicBarrier, Phaser, and Exchanger

-  Concurrent Collections (already discussed during Collections topic, will provide working example for this)
    * ConcurrentHashMap
    * ConcurrentLinkedQueue and ConcurrentLinkedDeque
    * CopyOnWriteArrayList
    * BlockingQueue Interface
        * ArrayBlockingQueue
        * LinkedBlockingQueue
        * PriorityBlockingQueue

-  Atomic Variables
    * AtomicInteger, AtomicLong, and AtomicBoolean
    * AtomicReference and AtomicReferenceArray
    * Compare-and-Swap Operations

-  Locks and Semaphores
    * ReentrantLock
    * ReadWriteLock
    * StampedLock
    * Semaphores
    * Lock and Condition Interface

-  Parallel Streams (already discussed during Stream topic, will provide working example for this)

-  Best Practices and Patterns
    * Thread Safety Best Practices
    * Immutable Objects
    * ThreadLocal Usage
    * Double-Checked Locking and its Issues
    * Concurrency Design Patterns

-  Common Concurrency Issues and Solutions
    * Deadlocks
    * Starvation
    * Livelocks
    * Race Conditions
    * Strategies for Avoiding Concurrency Issues

-  Java 9+ Features
    * Reactive Programming with Flow API
    * CompletableFuture Enhancements
    * Process API Updates

-  Java 11+ Features
    * Local-Variable Type Inference (var keyword)
    * Enhancements in Optional class
    * New Methods in the String class relevant to concurrency
___
>Type of Memory (Stack and Heap)
- What kind of data is Stored in Stack and Heap with Example
- Types of References
  - Strong Reference
  - Weak Reference
  - Soft Reference
- Heap Memory Structure
  - Young Generation
  - Eden
  - Survivor (S0 and S1)
  - Old Generation
  - Metaspace
- How Garbage Collector work & clean up the Heap memory with Example
- Types of Garbage Collector
  - Single GC
  - Parallel GC
  - CMS (Concurrent Mark and Sweep)
    - G1 GC