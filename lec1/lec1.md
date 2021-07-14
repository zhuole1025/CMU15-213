# Course Overview
## Course Theme
* This course is more about the details of uderlying implementations
* Useful outcomes from taking this course
    * Become more effective programmers
    * Prepare for later "system" classes
* Great Reality
    * Ints are not Integers, Floats are not Reals  
      ```shell
      lldb
      print 50000 * 50000 # Overflow
      print 40000 * 40000
      ```
        * Due to finiteness of representations
        * Integer operations satisfy "ring" properties
            * Commutativity, associativity, distributivity
        * Floating point operations satisfy "ordering" properties
            * Monotonicity, values of signs
    * You've Got to Know Assembly
        * Understanding assembly is key to machine-level executions model
    * Memory Matters
        * Memory is not unbounded
        * Memory referencing bugs
            * C and C++ do not provide memory protection, which can lead to nasty bugs
        * Memory performance is not uniform
    * There's more to performance than asymptotic complexity
        * Constant facttors matter too
        * Exact operation count does not predict performance
        * Must understand system to optimize performance
    * Computers do more than execute programs
        * They need to get data in and out (I/O system critical to program reliability and performance)
        * They communicate with each other over networks, and many system-level issues arise in presence of network

