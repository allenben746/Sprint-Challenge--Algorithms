#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n^2) - the function only runs as many times as 'n', the 'n*n*n' and 'n*n' cancel eahother out and leave it as 'n'

b) O(n^2) - the function loops through 'n', nothing special  

c) O(log n) - the function operates over bunnyEars 'n' + 1 times

## Exercise II

- Start at floor that is equal to n/2
- If egg breaks go down halfway, else go up halfway (go up/down **(n//2{Latest n//2}//2))
- example: n=100
- start at floor 50
- drop egg, if breaks go down to 25, else go up 25
- repeast until the floor above breaks egg but the floor you are on doesn't break the egg
