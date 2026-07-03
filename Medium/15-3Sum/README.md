# 15. 3Sum

**Difficulty:** Medium  
**Status:** ✅ Accepted  
**Runtime:** 35ms | Beats 44.04%  
**Memory:** 59.17 MB | Beats 59.69%  
**Test Cases:** 316 / 316 passed  
**Date Solved:** 2026-07-02  
**Link:** https://leetcode.com/problems/3sum/

## Problem

Given an integer array `nums`, return all the triplets `[nums[i], nums[j], nums[k]]`  
such that `i != j`, `i != k`, `j != k`, and `nums[i] + nums[j] + nums[k] == 0`.

**Example:**
```
Input:  nums = [-1,0,1,2,-1,-4]
Output: [[-1,-1,2],[-1,0,1]]
```

## Approach — Two Pointers

1. Sort the array
2. Fix one element, use two pointers (left & right) to find pairs that sum to zero
3. Skip duplicates to avoid repeated triplets

**Time Complexity:** O(n²)  
**Space Complexity:** O(1)

