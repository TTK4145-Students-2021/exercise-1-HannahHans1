The two threads/goroutines increment and decrement the variable i 1000000 times. However, the final value of i is not zero, 
and the result changes for each execution of the program. The problem is that the threads share the same memory and the swapping is unpredictable. 
This situation is called a race condition.
The swapping to the other task can occur while the first one is moditying i, causing the task to
overwrite the last changes.
