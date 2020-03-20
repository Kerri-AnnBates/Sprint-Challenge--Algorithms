#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)
Runtime: Worst case is O(n), best case O(1)
Because the operation will run n number of times. If a is 10 and n is 5*5*5, the operation will execute 1 + n times which is essentially O(n).

b)
o(n) + o(1) \* o(n) + o(1) + o(1)
Runtime: Worst case: O(n)

Because the inner loop will only run once based on the input from n due to j being doubled in the while loop to end the while loop. And the for loop will run n times.

c)
Runtime: O(n)

Because the recursive function is calling itself one time per n which is "bunnies".

## Exercise II

We can check what floor the egg breaks are minimized by starting on a middle floor and throw your eggs. If most of your eggs break, you know to go do a check on the lower floor, if most are unbroken, you can check the higher floors. Then do that strategy again until you determine the floor that the number of eggs is minimized.

I would say the time complexity would be O(log(n)) because you're cutting your chances of finding the correct floor in half every time you do a test.
