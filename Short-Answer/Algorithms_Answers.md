#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)


b) O(n**2)


c) O(n)

## Exercise II
If the number of floors is equal to 1, that is the break floor.
Else, split the floors of the building equally into lower half and upper half.
Round down if odd number of floors. Drop an egg at the halfway floor.
If egg breaks, ignore upper half and repeat process. If egg does not break, ignore lower half and repeat process.

Time complexity is O(logn).
