---
description: Rotating 2d array
---


# Rotating 2d Array

Given an `nxn` two-dimensional matrix of numbers, rotate the matrix 90 degrees to the right (clockwise).

Leetcode problem Link : https://leetcode.com/problems/rotate-image/description/

```json title="Input"
[
  [ 1,  2,  3, 4],
  [ 5,  6,  7, 8],
  [ 9, 10, 11, 12],
  [13, 14, 15, 16]
]
```
 .  
```json title="Output"
[
 [13,  9, 5, 1],
 [14, 10, 6, 2],
 [15, 11, 7, 3],
 [16, 12, 8, 4]
]
```

| 1 | 2 | 3 | 4 |
|---|---|---|---|
| 5 | 6 | 7 | 8 |           
| 9 | 10 | 11 | 12 |
| 13 | 14 | 15 | 16 |


| 13 | 9  | 5 | 1 |
|---|---|---|---|
| 14 | 10 | 6 | 2 |
| 15 | 11 | 7 | 3 |
| 16 | 12 | 8 | 4 |




