# 🟡 Median of Two Sorted Arrays

**Problem link:** [Integer to Roman](https://leetcode.com/problems/integer-to-roman/)  
**Difficulty:** Medium  
**Runtime:** 11 ms  
**Memory Usage:** 17.7 MB  

### 🧠 Approach
- Use a dictionary that maps integer values to their Roman numeral representations (including subtractive cases like `IV`, `IX`, `XL`, etc.).
- Sort the dictionary in descending order by value.
- Greedily subtract the largest possible Roman numeral value from the integer until it reaches 0, appending the corresponding Roman numeral to the result string.
