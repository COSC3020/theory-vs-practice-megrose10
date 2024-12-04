# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

Add your answers to this markdown file.


Part 1:
1. Depending on the memory the machine has, or the program acquires, this can slow runtime. For example, if your program uses up a lot of memory, this can slow things down. Like if you had a bunch of arrays, strings, etc your program was looking through and there was not a way to get rid of memory you don't need, this can cause issues down the line.
2. Like in the slides, having a more simple approach for some problems may not work for others. For example, if using memoization, if you are not reusing things you already calculated this slows the program down, but if you used this method for exaple a fib sequence, this would be faster.
3. Depending on the machines the code runs on, the same code can vary in time. Asymptotic analysis does not take in external variables.

Part 2:
Within binary trees, they usually have a complexity of log2(n). So, to find the estimated runtime we can find this by inputting our values. For 1000 elements the runtime is estimated at log2(1000) = 9.9 seconds. For 10000 elements, the runtime is estimated at log2(10000) = 13.3 seconds. This is just an estimation. To see how the logarithmic graph grows to these two points, we can divide them to see how much they grow, (13.3/9.9) = 1.34. So, now taking into account the runtime we are given for 1000 elements which is 5 seconds, we can multiply our rate that goes from 1000 to 10000 by the number resulting in 5 * 1.34 = 6.7 seconds. 

Part 3:
1. Like above, depending on how much memory this program takes up, runtime may be slower. So, if you are going through elements and keeping everything in memory, this program will get slower and slower with less memory being available. With 10000 elements, this will keep becoming less and less memory effecient.
2. Depending on the implementation, if the code is very very ineffcient, the time can become much larger. 
3. A machine may do fine handling a few elements, but as the time increases, certain machines may do worse and worse with runtime.   

Citations:
I used lecture notes and slides to base my answers on. I wasn't fully sure if my formula was correct so I tried to search online to see what a binary search tree formula would be but resulted in trying to put log base 1000 in the calculator to check if the formula was right. I worked with Olivia, Ashlyn, and Cole(Nathanial). I was unsure on how to find the growth rate for question 2 on why the time was different from my guess of 9.9 seconds and the given time 5 seconds, so I asked chatGPT which showed me finding the ratio of the two runtimes finds the growth rate. 

I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.
