#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - outer (O(n^3) - inner)


b) O(log(n)) see Anthony DM


c) O(n) We to will round down the quotient of n divided by 2 (n//2)

## Exercise II
If the egg breaks, we insert {f: false} to the right of the tree, where f is the floor and false is survival of the egg. Then we run again from floor f // 2 

If the egg doesn't break, we insert {f: true} to the left of the tree, where f is the floor and true is survival of the egg. Then we run from (n + f) // 2 meaning half of the point between middle and top 

we repeat this process until the BST's get_max ( or condition that the egg survived ) returns true and also the BST's contains method returns true for a value 1 higher than the max.

O(log(n)) since the function will run less than once per n

