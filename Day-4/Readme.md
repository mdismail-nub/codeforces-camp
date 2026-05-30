# 59A - Word

**Problem Link:** https://codeforces.com/problemset/problem/59/A

## Approach
- Count uppercase and lowercase letters.
- If uppercase letters are strictly greater than lowercase letters, convert the whole string to uppercase.
- Otherwise, convert it to lowercase.

## Complexity
- Time: O(n)
- Space: O(1)



# 977A - Wrong Subtraction

**Problem Link:** https://codeforces.com/problemset/problem/977/A

## Approach
- Read `n` and `k`, then simulate the process `k` times.
- At each step, if the last digit of `n` is non-zero, subtract 1 from `n`.
- If the last digit of `n` is zero, divide `n` by 10 (remove the last digit).
- Print the result after all `k` operations.

## Complexity
- Time: O(k)
- Space: O(1)
