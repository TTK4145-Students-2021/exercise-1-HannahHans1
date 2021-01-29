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
 > *Your answer here*
 
 ### What is the conceptual difference between threads and processes?
 > Threads share memory between them, while processes don't.
 
 ### Some languages support "fibers" (sometimes called "green threads") or "coroutines"? What are they?
 > *Your answer here*
 
 ### What is the Go-language's "goroutine"? A C/POSIX "pthread"?
 > *Your answer here*
 
 ### In Go, what does `func GOMAXPROCS(n int) int` change? 
 > *Your answer here*



 
 
 
 
