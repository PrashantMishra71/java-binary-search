# Binary Search

## Problem Statement

Given a sorted array and a target value, find the index of the target using binary search.

Return `-1` if the target does not exist in the array.

## Example

Array:

[1, 3, 5, 7, 9, 11]

Target:

7

Output:

Target Index: 3

## Approach

Binary Search repeatedly divides the search space into two halves.

1. Set `left` to the first index.
2. Set `right` to the last index.
3. Calculate the middle index.
4. If the middle element equals the target, return its index.
5. If the target is smaller, search the left half.
6. If the target is larger, search the right half.
7. Continue until the target is found or the search space becomes empty.

The array must be sorted for binary search to work correctly.

## Complexity

- Time: O(log n)
- Space: O(1)

Where `n` is the number of elements in the array.

## Concepts Practiced

- Binary Search
- Arrays
- Divide and Conquer
- Iteration
- Search Space Reduction