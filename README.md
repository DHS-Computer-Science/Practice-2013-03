# Practice 2013 - 03: More Dice

## Background
You roll two standard six-sided dice. Given the sum of your roll, determine the
dice combinations that would result in that sum. Only list unique dice
combinations:
- e.g. (1,6) and (6,1) are equivalent. List only one of these.

## Description

### Input
The first line of input is the number of test cases that follow.

Each input case appears on a single line, and will be a single integer; the sum
of a roll of two 6-sided dice.

There will be at most 1000 input cases.

### Output
For each case, output the line “Case x:” where x is the case number, on a single
line. Then output a list of possible dice-pairs that result in that sum, one on
each line. Each dice-pair should be comma-separated and enclosed by parentheses.
In each pair, the die values should be ordered from lowest to highest. The pairs
should also be ordered from lowest to highest based on the lowest die.

## Sample
### Input
```
2
7
5
```

### Output
```
Case 1:
(1 ,6)
(2 ,5)
(3 ,4)
Case 2:
(1 ,4)
(2 ,3)
```
