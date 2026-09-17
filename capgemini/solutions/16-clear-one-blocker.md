# C16: Clear one blocker — solution

**Answer:** 4 moves: A D, A D, X R, X R.

1. Move **A** one cell **down**.
2. Move **A** one cell **down**.
3. Move **X** one cell **right**.
4. Move **X** one cell **right**.

X now touches the right edge. A search of all legal board states by move count reaches the goal for the first time after **4 moves**. This checks that a shorter sequence is not possible under these rules. Other shortest sequences may also work.

**Watch out:** Count each one-cell shift. Moving a block out of the way may take more than one move.

[Back to the problem](../problems/16-clear-one-blocker.md) · [Question list](../README.md)
