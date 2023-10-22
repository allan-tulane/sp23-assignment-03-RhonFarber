# CMPS 2200 Assignment 3
## Answers

**Name:**Rhon Farber


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**
For the iterative solution:
W(n) = O(n) because iterate goes through every string in mylist.
S(n) = O(n) because iterate is sequential, so no parallelism.

- **d.**
Assuming efficient scan implementation and that any maps are done in parallel:
W(n) = W(n/2) + n ∈ O(n) because every element in the list is mapped
S(n) = S(n/2) + 1 ∈ O(log n) because of scan

- **f.**
Assuming any recursive calls are done in parallel:
W(n) = 2W(n/2) + 1 ∈ O(n) because going through mylist is O(n) and merging is O(1)
S(n) = S(n/2) + 1 ∈ O(log n)
