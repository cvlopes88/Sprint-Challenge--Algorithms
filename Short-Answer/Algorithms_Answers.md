#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I
Given 3 blocks of code, identify the runtime of each. Justify your answer.
a)Runtime: O(n)
the function its O(n) because the loop will run until n^3 and a is increasing each time n^2 each time 

b)Runtime: O(n*log(n))
The for loop runs n times and the inner while loop runs approximately log(n) times. This is because the variable j increments exponentially until it reaches n

c)Runtime: O(n)
The function will be recursively called n+1 times
## Exercise II


lets get a start floor of 1 and the last floor = n.
if last - start > 0 drop egg from middle floor if egg breaks thats f if it does not make it the end floor and find new middle and do the same thing
