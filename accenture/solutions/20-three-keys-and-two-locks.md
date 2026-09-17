# A20: Three keys and two locks — solution

**Answer:** 19 moves. One shortest route is `DDDDRRRRRLUUUURRDDD`.

Follow this route:

`R1C1 → R2C1 → R3C1 → R4C1 → R5C1 → R5C2 → R5C3 → R5C4 → R5C5 → R5C6 → R5C5 → R4C5 → R3C5 → R2C5 → R1C5 → R1C6 → R1C7 → R2C7 → R3C7 → R4C7`

Pick up key **b** on move **2**. Pick up key **c** on move **9**. Pick up key **a** on move **16**. Enter E on move **19**.

To check the minimum, count routes in layers: all states after 1 move, then 2 moves, and so on. A state includes both your cell and the keys you have. The first layer that reaches E with all keys is layer 19. The included checker repeats this search.

**Watch out:** A shorter walk to the exit does not count if you have missed a key.

[Back to the problem](../problems/20-three-keys-and-two-locks.md) · [Question list](../README.md)
