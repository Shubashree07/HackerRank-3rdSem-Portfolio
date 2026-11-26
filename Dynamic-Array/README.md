
# Dynamic Array

- Platform: HackerRank
- Language: Java 15
- Difficulty: Easy
- Topic: Data Structures, Dynamic Arrays, Bitwise XOR
- Status: Accepted

## Approach
1. Create N empty sequences using ArrayLists.
2. Calculate the sequence index using (x ^ lastAnswer) % n.
3. For query type 1, append the value Y.
4. For query type 2, retrieve the required element and update lastAnswer.
5. Store each type 2 answer in the result list.

## Complexity Analysis
- Time Complexity: O(N + Q)
- Space Complexity: O(N + Q)

## Concepts Learned
- ArrayList
- Nested lists
- Bitwise XOR
- Modulo operation
- Query processing
