# C15: Swap filled and empty

**Type:** Inductive pattern matching  
**Level:** Medium  
**Practice time:** 45–75 seconds (a practice target, not an official limit)

The two examples follow the same rule. Choose the rule from the list, then choose **exactly two** option grids that follow it. X is filled; a dot is empty. Judge only the rules listed here.

**Example 1**

```text
    1 2 3 4
 1  X X . .
 2  . . X X
```

**Example 2**

```text
    1 2 3 4
 1  X . X .
 2  . X . X
```

**Possible rules**

1. Both rows are identical.
2. Only the middle cells may contain X.
3. The bottom row changes each X to a dot and each dot to X.

**Options**

**A**

```text
    1 2 3 4
 1  X . . X
 2  . X X .
```

**B**

```text
    1 2 3 4
 1  X X . .
 2  X X . .
```

**C**

```text
    1 2 3 4
 1  . . . .
 2  X X X X
```

**D**

```text
    1 2 3 4
 1  . X X .
 2  . X X .
```



Write your answer before opening the solution.

[Check the solution](../solutions/15-swap-filled-and-empty.md) · [Question list](../README.md)
