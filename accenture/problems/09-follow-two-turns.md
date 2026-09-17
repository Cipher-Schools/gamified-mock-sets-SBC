# A09: Follow two turns

**Type:** Path tracing  
**Level:** Medium  
**Practice time:** 60–90 seconds (a practice target, not an official limit)

A token starts at **R2C1**, facing **R**. It moves one cell at a time. A letter U, D, L or R changes its direction when it reaches that cell. A dot keeps its direction unchanged.

```text
    1 2 3 4 5
 1  . . . . R
 2  S . . D .
 3  . . . . .
 4  . L . . .
 5  . . . . .
```

The original tile under S is **S**. Apply it before the first move if it is an arrow.

Does the token leave the board or loop? If it leaves, count all moves, including the final move off the board. The starting cell is zero moves.

Write your answer before opening the solution.

[Check the solution](../solutions/09-follow-two-turns.md) · [Question list](../README.md)
