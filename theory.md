Exercise 1 - Theory questions
-----------------------------
 
 ### What is the difference between concurrency and parallelism?
 > Cuncurrency means that multiple tasks starts, run and complete seemingly simultaneously. Different tasks do not execute at the same time instance, but the CPU and memory resources is assigned to different tasks ecexuting in an overlapping time periode by a procedure called scheduling. The CPU switches between threads. In parallelism, however, tasks is executed at the same time instance on a multicore CPU.
 
 ### Why have machines become increasingly multicore in the past decade?
 > A multi-core CPU has a better performance than a single-core CPU. It is easier and more energy effective to increase the number of cores than increase the speed of a single core.
 
 ### Why do we divide software (programs) into concurrently executing parts (like threads or processes)?
 (Or phrased differently: What problems do concurrency help in solving?)
 > To increase the performance? One task does not have to wait until the previous task has completed. If a thread for some reason has to wait, the other threads can continue its procedure.
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 (Come back to this after you have worked on part 4 of this exercise)
 > Yes and no - it solves a problem and introduces others. Concurrent programs are more time efficient, at the cost of more complexity. (At least in problem 4) Concurrency give rise to issues like race condition. 
 
 ### What is the conceptual difference between threads and processes?
 > Threads share memory between them, while processes don't.
 
 ### Some languages support "fibers" (sometimes called "green threads") or "coroutines"? What are they?
 > A fiber is a lightweighted unit of execution that is cooperatively scheduled. A thread can run multiple fibers. A coroutine is a cooperative scheduling mechanism where the programmer decides when to swap between tasks.
 
 ### What is the Go-language's "goroutine"? A C/POSIX "pthread"?
 > A goroutine is a thread of execution in the Go-language. Multiple goroutines can execute concurrently. 
A pthread is a thread that is implemented according to the POSIX standard.
 
 ### In Go, what does `func GOMAXPROCS(n int) int` change? 
 > The function changes the maximum number of CPUs that can be executing simultaneously.



 
 
 
 
