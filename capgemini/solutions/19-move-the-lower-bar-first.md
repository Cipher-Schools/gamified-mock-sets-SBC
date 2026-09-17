# C19: Move the lower bar first — solution

**Answer:** 9 moves: B L, A D, A D, A D, X R, X R, C U, X R, X R.

1. Move **B** one cell **left**.
2. Move **A** one cell **down**.
3. Move **A** one cell **down**.
4. Move **A** one cell **down**.
5. Move **X** one cell **right**.
6. Move **X** one cell **right**.
7. Move **C** one cell **up**.
8. Move **X** one cell **right**.
9. Move **X** one cell **right**.

X now touches the right edge. A search of all legal board states by move count reaches the goal for the first time after **9 moves**. This checks that a shorter sequence is not possible under these rules. Other shortest sequences may also work.

**Watch out:** Count each one-cell shift. Moving a block out of the way may take more than one move.

[Back to the problem](../problems/19-move-the-lower-bar-first.md) · [Question list](../README.md)
