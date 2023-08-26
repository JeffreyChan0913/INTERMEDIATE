# Decode System

## time limit per test case: 1 second 

We encode a stringi, S, with the following rules
1. If the letter is a signle digit $S_i < 10$, we simply just use that digit. 
2. if the letter is two digits that is $S_i \geq 10$, then we use that two digits and add a 0 right after it. 

If the given string is 18100, then can think of it as the following: 
1. ```a``` is located the first value, so 1.
2. ```h``` is located at the 8th position, so 8
3. ```j``` is located at the 10th position, so 10 + 0

As a result ```18100``` is decoded as ```ahj```.

input:

test case number, $ 1 \leq t \leq 10^4 $
n digits to take in and $ 1 \leq n \leq 50 $
n digits to be read, expect the resultant is in lowercase. 

```
3
5
18100
3
123
6
100100
```

output:
```
ahj
abc
jj
```

