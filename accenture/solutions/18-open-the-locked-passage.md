# A18: Open the locked passage — solution

**Answer:** 5 moves. One shortest route is `RRRRR`.

Follow this route:

`R1C1 → R1C2 → R1C3 → R1C4 → R1C5 → R1C6`

Pick up key **a** on move **2**. Enter E on move **5**.

To check the minimum, count routes in layers: all states after 1 move, then 2 moves, and so on. A state includes both your cell and the keys you have. The first layer that reaches E with all keys is layer 5. The included checker repeats this search.

**Watch out:** A shorter walk to the exit does not count if you have missed a key.

[Back to the problem](../problems/18-open-the-locked-passage.md) · [Question list](../README.md)
