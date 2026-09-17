# A17: Collect both keys — solution

**Answer:** 16 moves. One shortest route is `DDDDUUUURRRRDDLL`.

Follow this route:

`R1C1 → R2C1 → R3C1 → R4C1 → R5C1 → R4C1 → R3C1 → R2C1 → R1C1 → R1C2 → R1C3 → R1C4 → R1C5 → R2C5 → R3C5 → R3C4 → R3C3`

Pick up key **b** on move **4**. Pick up key **a** on move **12**. Enter E on move **16**.

To check the minimum, count routes in layers: all states after 1 move, then 2 moves, and so on. A state includes both your cell and the keys you have. The first layer that reaches E with all keys is layer 16. The included checker repeats this search.

**Watch out:** A shorter walk to the exit does not count if you have missed a key.

[Back to the problem](../problems/17-collect-both-keys.md) · [Question list](../README.md)
