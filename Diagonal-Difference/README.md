
# 1. Diagonal Difference

**Platform:** HackerRank  
**Difficulty:** Easy  
**Language:** Java 15  
**Topic:** 2D Arrays / Matrices  
**Status:** Accepted

## Problem Description
Calculate the absolute difference between the sums of the primary and secondary diagonals of a square matrix.

## Approach
1. Find the size of the matrix.
2. Traverse the matrix using a single loop.
3. Add elements at arr[i][i] to the primary diagonal sum.
4. Add elements at arr[i][n-1-i] to the secondary diagonal sum.
5. Return the absolute difference between both sums.

## Complexity Analysis
- **Time Complexity:** O(N)
- **Auxiliary Space Complexity:** O(1)

## Concepts Learned
- 2D Array traversal
- Primary and secondary diagonals
- Absolute value using Math.abs()

## HackerRank Result
Accepted — 10/10 points.
