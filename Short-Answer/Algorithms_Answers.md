#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) because it is while a < n^3 and we are increasing by a by n^2 each iteration. So dividing n^3 by n^2 tells us the order of the function is n


b) This is O(n log(n)) because j doubles each iteration of the loop, and the condition that is being checked for is that j remains less than n. But meanwhile the bigger loop goes through every value for the range n. 


c) This is O(n) because it is a recursive function. It calls itself N times (or possibly N + 1 but we can drop the 1 ) before hitting the base case of bunnies == 0 . 

## Exercise II


set floor to 1
loop through this: 
    drop egg
    if breaks f = Floor
    else increase the floor by 1 

This is an O(n) solution that minimizes number of broken eggs to 1. 