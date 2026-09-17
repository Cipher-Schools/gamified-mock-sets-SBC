# C17: Choose the open space

**Type:** Motion planning  
**Level:** Medium  
**Practice time:** 2–4 minutes (a practice target, not an official limit)

Slide the blocks to bring **X to the right edge of its row**. Letters with the same name form one block. A dot is an empty cell.

- A horizontal block moves left or right. A vertical block moves up or down.
- One move shifts one whole block by **one cell**. Moving three cells costs three moves.
- Blocks cannot rotate, overlap, jump over another block, or leave the board.
- Finish when the right end of X touches the right edge. Do not count an extra move outside.

```text
    1 2 3 4 5
 1  . . . . .
 2  . . A . .
 3  X X A . .
 4  . B B . .
 5  . . . . .
```

Find the fewest moves. Write the block name and direction for each move. This is a small paper adaptation of a motion-planning game; the live game may use different controls.

Write your answer before opening the solution.

[Check the solution](../solutions/17-choose-the-open-space.md) · [Question list](../README.md)
