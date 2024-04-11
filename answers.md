# CMPS 2200 Recitation 06
## Answers

**Name:**______Gavin Galusha___________________
**Name:**_______Isaac Ratzaan__________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
- The time complexity for the recurrence relation W(n) = W(n-1) + W(n-2) + 1 follows an exponential growth pattern, similar to the Fibonacci sequence. Hence, it is classified as O(2^n).

- **3)**
The recurrence relation S(n) = S(n-1) + 1 describes a linear sequence where each term is incremented by one from the previous term, resulting in a time complexity of O(n).
- **4)**
- The given function mimics the generation of the Fibonacci sequence but starts with a specific number and increments by one in each step due to the constant term in the recurrence. This results in a shifted Fibonacci sequence starting from an initial value.

- **6)**
For any input i, the function fib_top_down() will be invoked at most i+1 times. Both the computational effort and the time to complete (span) are linear with respect to i, resulting in a complexity of O(n)
- **8)**
The function F_i is called at most n-2 times for calculating the nth term, and the process cannot be parallelized effectively. Both the computational workload and the time complexity (span) for this algorithm are O(n).