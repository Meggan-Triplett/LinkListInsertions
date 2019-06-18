# Linked List Insertions
#### *Author: Meggan Triplett*

------------------------------

## Problem Domain

.append(value) which adds a new node with the given value to the end of the list
.insertBefore(value, newVal) which add a new node with the given newValue immediately before the first value node
.insertAfter(value, newVal) which add a new node with the given newValue immediately after the first value node

------------------------------

## Inputs and Expected Outputs

.append(value)
| Input | Expected Output |
| :----------- | :----------- |
| 5 | head -> [1] -> [3] -> [2] -> [5] -> X |
| 1 | head -> [1] -> X |

.insertBefore(value, newVal)
| Input | Expected Output |
| :----------- | :----------- |
| 3, 5 | head -> [1] -> [5] -> [3] -> [2] -> X |
| 2, 5 | head -> [1] -> [5] -> [2] -> [2] -> X |

.insertAfter(value, newVal)
| Input | Expected Output |
| :----------- | :----------- |
| 3, 5 | head -> [1] -> [3] -> [5] -> [2] -> X |
| 2, 5 | head -> [1] -> [3] -> [2] -> [5] -> X |
------------------------------

## Big O


| Time | Space |
| :----------- | 
| O(n) | O(n) |


------------------------------


## Whiteboard Visual
![Screenshot of White Board](\assets\WhiteBoardScreenShot.jpg)


------------------------------

## Change Log

------------------------------
