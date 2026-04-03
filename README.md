# Next Permutation (LeetCode 31)

## 🧩 Problem Statement
Given an array of integers, rearrange it into the next lexicographically greater permutation.

If such an arrangement is not possible, rearrange it into the lowest possible order (ascending).

---

## 🚀 Approach

1. Traverse from right to find the first decreasing element (`i`).
2. Find the element just greater than `nums[i]` from the right (`j`) and swap them.
3. Reverse the subarray from `i + 1` to end.

---

## ⏱ Complexity
- Time Complexity: **O(n)**
- Space Complexity: **O(1)** (in-place)

---
