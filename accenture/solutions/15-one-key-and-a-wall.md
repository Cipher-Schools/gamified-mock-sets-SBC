# A15: One key and a wall — solution

**Answer:** 7 moves. One shortest route is `RRDDRRD`.

Follow this route:

`R1C1 → R1C2 → R1C3 → R2C3 → R3C3 → R3C4 → R3C5 → R4C5`

Pick up key **a** on move **3**. Enter E on move **7**.

To check the minimum, count routes in layers: all states after 1 move, then 2 moves, and so on. A state includes both your cell and the keys you have. The first layer that reaches E with all keys is layer 7. The included checker repeats this search.

**Watch out:** A shorter walk to the exit does not count if you have missed a key.

[Back to the problem](../problems/15-one-key-and-a-wall.md) · [Question list](../README.md)
