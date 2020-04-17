#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
This looks like it will be an infinite loop (unless the algorithm is changed)

b)
this looks like O(n) complexity as it iterates through one for loop

c)
this looks like o(n) complexity recursion as it calls itself once
## Exercise II
We can make a few assumptions with this problem. First lower floors are less
likely to break an egg, and second is the opposite, higher floors have a higher
chance of breaking an egg.
Starting from the bottom move up the floors in a small proportion (1/4) and drop
an egg. If the egg doesn't break move up another 1/4, if it does, moves down
half of the last step (1/8) and drop an egg (increasing by half 1/16 if it
doesn't break)
You will find a solution when adjacent floors have break and no break results.
