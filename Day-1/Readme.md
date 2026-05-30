# Day-1 Codeforces Problems

This folder contains solutions to several Codeforces problems from Day 1 of the camp.

## Bit++

**Problem Link:** https://codeforces.com/problemset/problem/282/A

### Approach
The program initializes a variable `x` to 0. It then reads an integer `n`, representing the number of operations. For each operation, it reads a string. If the string indicates an increment operation (e.g., "X++" or "++X"), `x` is incremented. If it indicates a decrement operation (e.g., "X--" or "--X"), `x` is decremented. Finally, the program prints the final value of `x`.

### Complexity
- Time: O(n), where `n` is the number of operations.
- Space: O(1)

## Next Round

**Problem Link:** https://codeforces.com/problemset/problem/158/A

### Approach
The program reads two integers, `n` (total participants) and `k` (the k-th place). It then reads `n` scores into an array. It iterates through the array, counting how many participants have a score greater than or equal to the score of the participant at the k-th position (index `k-1`) and also strictly greater than 0. This count represents the number of participants who will advance.

### Complexity
- Time: O(n), where `n` is the number of participants.
- Space: O(n), for storing the participants' scores.

## Team

**Problem Link:** https://codeforces.com/problemset/problem/231/A

### Approach
The program reads an integer `t`, representing the number of problems. For each problem, it reads three integers (`x`, `y`, `z`) indicating whether each of three friends is sure about the solution (1 for sure, 0 for not sure). A counter `cnt` is incremented if at least two friends are sure about the solution for a given problem. The final value of `cnt` is printed.

### Complexity
- Time: O(t), where `t` is the number of problems.
- Space: O(1)

## Watermelon

**Problem Link:** https://codeforces.com/problemset/problem/4/A

### Approach
The program reads an integer `a`, representing the weight of a watermelon. It checks if the weight `a` is an even number and is also greater than 2. If both conditions are met, it prints "YES"; otherwise, it prints "NO".

### Complexity
- Time: O(1)
- Space: O(1)

## Way Too Long Words

**Problem Link:** https://codeforces.com/problemset/problem/71/A

### Approach
The program reads an integer `t`, representing the number of words. For each word, it reads a string `s`. If the length of `s` is strictly greater than 10 characters, it prints an abbreviation: the first character of the word, followed by the number of characters between the first and last (length - 2), and then the last character. If the word's length is 10 or less, the word is printed as is.

### Complexity
- Time: O(t * L), where `t` is the number of words and `L` is the average length of a word.
- Space: O(L), for storing each word.
