# A19: Pick the key order — solution

**Answer:** 16 moves. One shortest route is `DDDDRRRRRUUUUDDL`.

Follow this route:

`R1C1 → R2C1 → R3C1 → R4C1 → R5C1 → R5C2 → R5C3 → R5C4 → R5C5 → R5C6 → R4C6 → R3C6 → R2C6 → R1C6 → R2C6 → R3C6 → R3C5`

Pick up key **b** on move **2**. Pick up key **c** on move **8**. Pick up key **a** on move **13**. Enter E on move **16**.

To check the minimum, count routes in layers: all states after 1 move, then 2 moves, and so on. A state includes both your cell and the keys you have. The first layer that reaches E with all keys is layer 16. The included checker repeats this search.

**Watch out:** A shorter walk to the exit does not count if you have missed a key.

[Back to the problem](../problems/19-pick-the-key-order.md) · [Question list](../README.md)
