#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - the number of operations increases linearly with the input size (n) due to the While loop.


b) O(nlogn) - the outer loop is O(n) and the nested loop is (log n) since j *= 2 is processing chunks of elements at a time, making the entire algorithm O(nlogn)


c) O(n) - Each time you make a recursive call has the runtime complexity of n. The base case is O(1) and the recursive case is O(n) since it makes one recursive call, which can all be simplified to O(n)

## Exercise II

Binary Search Approach - runtime of O(logn)

Start at the floor that is in the middle of the building (n // 2)
Drop and egg
If egg doesnt break, move to the floor that is the halfway point between where you currently are and the max floor
If egg breaks, move to the floor that is the halfway point between the min floor and where you currently are
Repeat the process of cutting floors in half until you are at the highest floor where an egg can be dropped and not break. That floor is the value of 'f'.
