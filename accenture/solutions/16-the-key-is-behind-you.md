# A16: The key is behind you — solution

**Answer:** 8 moves. One shortest route is `LLUURRRR`.

Follow this route:

`R3C3 → R3C2 → R3C1 → R2C1 → R1C1 → R1C2 → R1C3 → R1C4 → R1C5`

Pick up key **a** on move **4**. Enter E on move **8**.

To check the minimum, count routes in layers: all states after 1 move, then 2 moves, and so on. A state includes both your cell and the keys you have. The first layer that reaches E with all keys is layer 8. The included checker repeats this search.

**Watch out:** A shorter walk to the exit does not count if you have missed a key.

[Back to the problem](../problems/16-the-key-is-behind-you.md) · [Question list](../README.md)
