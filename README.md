# Dungeon Health Points Calculator

This project contains a solution to the problem of calculating the minimum health points required for a knight to traverse a dungeon represented by a 2D grid. The knight must ensure that he has at least 1 health point at all times while moving from the top-left corner to the bottom-right corner of the dungeon.

## Problem Description

In the dungeon, each cell can have a positive or negative value:
- A positive value represents health points gained.
- A negative value represents health points lost.

The goal is to determine the minimum health points the knight needs to start with in order to reach the princess located at the bottom-right corner of the dungeon.

## Functionality

The main function provided in this project is:

```python
class Solution:
    def calculateMinimumHP(self, dungeon: List[List[int]]) -> int:
