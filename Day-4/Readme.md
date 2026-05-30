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



# 110A - Nearly Lucky Number

**Problem Link:** https://codeforces.com/contest/110/problem/A

## Approach
- Lucky digits are `4` and `7`. A number is called a lucky number if it contains only these digits.
- Count how many lucky digits (4s and 7s) are present in the given number `n`.
- If that count itself is a lucky number (i.e., equal to `4` or `7`), print `YES`.
- Otherwise, print `NO`.

## Complexity
- Time: O(log n)
- Space: O(1)

