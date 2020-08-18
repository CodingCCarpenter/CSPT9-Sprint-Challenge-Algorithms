#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) is the runtime complexity because the while loop only runs through an additional n times


b) O(n^2) because we nested loops that both run a number that is proportionate to n


c) We to will round down the quotient of n divided by 2 (n//2)

## Exercise II
If the egg breaks, we insert {f: false} to the right of the tree, where f is the floor and false is survival of the egg. Then we run again from floor f // 2

If the egg doesn't break, we insert {f: true} to the left of the tree, where f is the floor and true is survival of the egg. Then we run from (n + f) // 2 meaning half of the point between middle and top

we repeat this process until the BST's get_max ( on condition that the egg survived ) returns true and also the BST's contains method returns true for a value 1 higher than the max.



