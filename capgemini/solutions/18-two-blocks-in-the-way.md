# C18: Two blocks in the way — solution

**Answer:** 5 moves: A U, X R, B U, X R, X R.

1. Move **A** one cell **up**.
2. Move **X** one cell **right**.
3. Move **B** one cell **up**.
4. Move **X** one cell **right**.
5. Move **X** one cell **right**.

X now touches the right edge. A search of all legal board states by move count reaches the goal for the first time after **5 moves**. This checks that a shorter sequence is not possible under these rules. Other shortest sequences may also work.

**Watch out:** Count each one-cell shift. Moving a block out of the way may take more than one move.

[Back to the problem](../problems/18-two-blocks-in-the-way.md) · [Question list](../README.md)
