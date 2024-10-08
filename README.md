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
1. Depending on the data structure the worst case of one might be the best case of another.
2. Not all cases will work for all code of a certain size.
3. Depending on the size of the data, some structures may do better than others.

Part 2:
Since binary search trees are using log base n it would take around 6 seconds. Since log base 1000 takes about 3 seconds but this runs a couple seconds more, I added 1 to log base 10000 to get a result of 6 seconds.

Part 3:
1. Depending on what you run the code on (computer) it can take longer.
2. Asymptotic complexity is an estimation, so depending on the type of data this may run slower.
3. If the data was not sorted in the beginning the program may take longer.

Citations:
I used lecture notes and slides to base my answers on. I wasn't fully sure if my formula was correct so I tried to search online to see what a binary search tree formula would be but resulted in trying to put log base 1000 in the calculator to check if the formula was right.

I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.
