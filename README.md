# Sorted Squares Algorithm

## Description
This Java solution sorts the squares of elements in a given integer array. It leverages a two-pointer approach to efficiently sort the squares of both negative and positive numbers.

## Key Steps:
- The algorithm starts with two pointers: one at the beginning (`start`) and one at the end (`end`) of the input array.
- It compares the squares of the elements at both pointers and places the larger square at the current position in a new result array (`ans`).
- The pointer associated with the larger square moves inward, while a third pointer (`ptr`) fills the result array from the end.
- The process continues until all elements are processed and the result array contains the squares sorted in non-decreasing order.

## Time Complexity:
- O(n), where `n` is the length of the input array, as each element is processed once.

This method efficiently handles both negative and positive numbers while maintaining an optimal time complexity.
