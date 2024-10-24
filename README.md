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
1. Asymptotic follows a formula that is a generalization, but depending on the code and how it is configured, the runtime can be much longer.
2. Not all cases will work for all code of a certain size.
3. Depending on the size of the data, some structures may do better than others.

Part 2:
Since binary search trees are using log2(n), then log2(1000) would be about 9.9 seconds, but with log2(10000) this would take about 13.3 seconds rounded. Since binary trees time grows at an exponential rate, the time between will keep increasing faster as the data increases. 

Part 3:
1. Depending on what you run the code on (computer) it can take longer.
2. Asymptotic complexity is an estimation, so depending on the type of data this may run slower.
3. Since binary trees can sometimes not be balanced, depending on how the tree is set up, the actual time could be longer than the asymtotic complexity. 

Citations:
I used lecture notes and slides to base my answers on. I wasn't fully sure if my formula was correct so I tried to search online to see what a binary search tree formula would be but resulted in trying to put log base 1000 in the calculator to check if the formula was right. I worked with Olivia, Ashlyn, and Cole(Nathanial). 

I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.
