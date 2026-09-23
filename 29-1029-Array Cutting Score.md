# 1029 Array Cutting Score

- **分值：** 35分

## 题目描述

Given an integer array of length $$n$$, cut the array into $$m$$ ($$\le n$$) subarrays by exactly $$(m-1)$$ cuts.  **Array cutting score** is defined to be the product of all the sums of the subarray elements.  Your job is to calculate the product of the scores of all the possible ways of array-cutting.

## Input Specification

Each input file contains one test case. For each case, the first line contains two positive integers $$n$$ and $$m$$ ($$1\le m \le n \le 10^3$$).  The second line contains $$n$$ positive integers no larger than $$10^9$$ separated by a single space..

## Output Specification

Output the product of the scores of all the possible ways of array-cutting in a single line. Since the answer might be too large, output the result modulo 1000000007 ($$10^9 + 7$$).

## Sample Input
```
5 2
5 1 2 3 4
```

## Sample Output
```
6652800
```

**Hint:**

- The score of cut (5)(1 2 3 4) is $$5 \times (1+2+3+4) = 50$$
- The score of cut (5 1)(2 3 4) is $$(5+1) \times (2+3+4) = 54$$
- The score of cut (5 1 2)(3 4) is $$(5+1+2) \times (3+4)= 56$$
- The score of cut (5 1 2 3)(4) is $$(5+1+2+3) \times 4 = 44$$
- The final result is $$50 \times 54 \times 56 \times 44 = 6652800$$
