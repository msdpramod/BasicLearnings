
What is Constructor

- Rules of Constructor
- Types of Constructor:
  - Default Constructor,
  - No Argument Constructor,
  - Parametrised Constructor,
  - Private Constructor,
  - Constructor Overloaded,
  - Constructor Chaining,
---
CLASS

- Concrete Class
- Abstract Class
- Super Class and Sub Class
- Object Class
- Nested Class
- Inner Class (Non Static Nested Class)
- Anonymous Inner Class
- Member Inner Class
- Local Inner Class
- Static Nested Class / Static Class
  • Generic Class
  • POJO Class
  • Enum Class
  • Final Class
  • Singleton Class
  • Immutable Class
  • Wrapper Class
---
GENERICS

- What is Generic Class and what is the need of it?
- How to define the Generic Class
- Inheritance with Generic Classes
  - Non Generic Subclass
  - Generic Subclass
- Multiple Type Parameters in Generic Class
- Generic Methods
- What is Raw Type
- Bounded Generics
    - Upper Bound
    - Multi Bound
- Wildcards
    - UpperBound
    - LowerBound
    - Unbounded
- Type Erasure
---
POJO 

- POJO Class
- Enum Class
    - Enum Class Properties
    - Normal Enum Class
    - Enum Class with Multiple Values
    - Overriding in Enum Class
    - Abstract Methods in Enum Class
    - Interface implementation in Enum
    - Why Enum is better than static final variables or constant classes
- Final Class
---
INTERFACES

- What is Interface.
- How to define Interface
- Why we need Interface
- Diamond Problem and Solution
- Method in Interface
- Fields in Interface
- Interface Implementation and Rules
- Nested Interface
  - Interface within Interface
  - Interface within a Class
- Abstract Class Vs Interface
- Java8 and Java9 Interface features
  - Default Method
  - Static Method
  - Functional Interface
  - Private Method
---
Java8 and Java9 Interface features

- Default Method
- Static Method
- Private Method
- Private Static Method
---
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
---
LAMBDA EXPRESSIONS

- What is Functional Interface?
- What is Lambda Expression?
- How to use Functional Interface with Lambda expression
- Advantage of Functional Interface?
- Types of Functional Interface?
  ○ Consumer
  ○ Supplier
  ○ Function
  ○ Predicate
- How to handle use case when Functional Interface extends from other Interface(or Functional Interface)?
---
REFLECTIONS

- What is "Class" class which JVM creates at runtime
- How to Reflect Classes and access its metadata
- How to Reflect Methods and access its metadata
- How to Invoke Methods using Reflection
- How to Reflect Fields and access its metadata
- How to access and change the value of Public field
- How to access and change the value of Private field.
- How to Reflect Constructor and access its metadata.
- How to access and invoke private constructor using reflection.
- How Reflection breaks Singleton design pattern and how to resolve.
---
EXCEPTION HANDLING

- What is Exception
- Exception Hierarchy
- Uncheck / Runtime Exception
- Checked / CompileTime Exception
- How to handle the Exception properly (try, catch, finally, throw, throws)
- Creating User-Defined Exception class
- Advantages of Exception Handling
- Disadvantage of Exception Handling
___
Type of Memory (Stack and Heap)

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