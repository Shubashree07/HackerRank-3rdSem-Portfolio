
# Time Conversion

- Platform: HackerRank
- Language: Java 15
- Difficulty: Easy
- Topic: Strings and Logic
- Status: Accepted

## Approach
1. Extract the AM/PM indicator.
2. Extract the hour from the input string.
3. For 12 AM, change the hour to 00.
4. For PM, add 12 unless the hour is already 12.
5. Preserve the minutes and seconds.

## Complexity Analysis
- Time Complexity: O(1)
- Space Complexity: O(1)

## Concepts Learned
- String manipulation
- Substring extraction
- Conditional statements
- 12-hour to 24-hour conversion
