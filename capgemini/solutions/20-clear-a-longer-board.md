# C20: Clear a longer board — solution

**Answer:** 13 moves: C L, A D, D L, B D, B D, D L, D L, A D, A D, X R, X R, X R, X R.

1. Move **C** one cell **left**.
2. Move **A** one cell **down**.
3. Move **D** one cell **left**.
4. Move **B** one cell **down**.
5. Move **B** one cell **down**.
6. Move **D** one cell **left**.
7. Move **D** one cell **left**.
8. Move **A** one cell **down**.
9. Move **A** one cell **down**.
10. Move **X** one cell **right**.
11. Move **X** one cell **right**.
12. Move **X** one cell **right**.
13. Move **X** one cell **right**.

X now touches the right edge. A search of all legal board states by move count reaches the goal for the first time after **13 moves**. This checks that a shorter sequence is not possible under these rules. Other shortest sequences may also work.

**Watch out:** Count each one-cell shift. Moving a block out of the way may take more than one move.

[Back to the problem](../problems/20-clear-a-longer-board.md) · [Question list](../README.md)
