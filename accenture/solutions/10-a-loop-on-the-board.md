# A10: A loop on the board — solution

**Answer:** It loops and never leaves the board.

Follow this route:

`R3C2 → R2C2 → R2C3 → R2C4 → R3C4 → R4C4 → R4C3 → R4C2 → R3C2`

The same position and direction occur again. From there, the route repeats.

**Watch out:** Returning to a cell is only a loop if the direction is also the same.

[Back to the problem](../problems/10-a-loop-on-the-board.md) · [Question list](../README.md)
