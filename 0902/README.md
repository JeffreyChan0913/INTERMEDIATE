<h2 align="center">0902</h2>

##### time limit per test case: 1 second 

### Problem 1 - Happy Factorial

You will be given an integer $n$ and you will need to find the largest integer $x$ such that it fulfills the following condition: $1 \leq x \leq n$ and $x! + (x-1)!$ is a multiple of $n$.

Say, $a,b,c \in \mathbb{Z}$ such that $a = b \times c$. For example, 10 is a multiple of 5. Example 2, 9 is not amultiple of 6.

test case [LINK](https://github.com/JeffreyChan0913/INTERMEDIATE/blob/main/0902/testcase.txt):

Input:

The first line contains a single integer t, $1 \leq t \leq 10^4$
The next $t$ lines, will contain an integer $n$ such that $2 \leq n \leq 10^9$

Output:
Output x if that satisfies the conditions from above, otherwise, output $-1$.

```
4
3
6
8
10
```

```
2
5
7
9
```

<font size = 1>Last Updated: 08-11-2023, 12:53:00 pm T2-173</font>

