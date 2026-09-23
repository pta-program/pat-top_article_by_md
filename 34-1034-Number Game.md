# 1034 Number Game

- **分值：** 35分

## 题目描述

A number game is to start from a given number $$A$$, and to reach the destination number $$B$$ by a sequence of operations.

For the current number $$X$$, there are 3 types of operations:
- $$X=X+1$$
- $$X=X-1$$
- $$X=X\times N$$

Your job is to find the minimum number of steps required to reach $$B$$ from $$A$$.

## Input Specification

Each input file contains several test cases.  The first line gives a positive integer K ($$\le$$10) which is the total number of cases.  For each case, three  integers are given: $$A$$, $$B$$ and $$N$$, where $$-10^5 \le A, B \le 10^5$$ and $$1<N<10$$.  All the numbers in a line are separated by a space.

## Output Specification

For each test case, print in a line the minimum number of steps required to reach $$B$$ from $$A$$.

## Sample Input
```
3
3 11 2
-5 -12 3
-2 1000 7
```

## Sample Output
```
3
2
13
```

## Hint

Case 1: $$(3\times 2\times 2)-1=11$$

Case 2: $$(-5+1)\times 3 = -12$$

Case 3: $$(((-2+1+1+1+1+1)\times 7 -1)\times 7 +1+1+1)\times 7-1 = 1000$$
