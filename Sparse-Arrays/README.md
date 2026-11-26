
# Sparse Arrays

- Platform: HackerRank
- Language: Java 15
- Difficulty: Medium
- Topic: Hash Maps and Strings
- Status: Accepted

## Problem Description
Given a collection of strings and a list of queries, determine how many times each query string occurs in the original collection.

## Approach
1. Create a HashMap to store string frequencies.
2. Traverse the original string list.
3. Increase the frequency of each string.
4. Traverse the query list.
5. Retrieve the frequency of each query using getOrDefault().
6. Store the results in a list and return it.

## Complexity Analysis
- Time Complexity: O(N + Q) average
- Space Complexity: O(N + Q), including the result list.

## Concepts Learned
- HashMap
- String frequency counting
- getOrDefault()
- ArrayList
- Efficient searching
