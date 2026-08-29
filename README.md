# LeetCode 70 – Climbing Stairs

You are climbing a staircase with `n` steps.

Each time, you can climb either:

* 1 step
* 2 steps

Return the number of distinct ways to reach the top.

## Example

### Input

```text
n = 5
```

### Output

```text
8
```

There are 8 different ways to reach the top.

## Approach

I used **Dynamic Programming**.

The number of ways to reach a step is the sum of the ways to reach the previous two steps.

This follows the Fibonacci pattern:

`ways(n) = ways(n-1) + ways(n-2)`

I only store the previous two values, so extra memory is kept small.

## Complexity

* **Time Complexity:** `O(N)`
* **Space Complexity:** `O(1)`

## Language

**Python**

## LeetCode

**Problem:** 70. Climbing Stairs
**Difficulty:** Easy
**Topic:** Dynamic Programming, Math

## Author

T.Nandhini
