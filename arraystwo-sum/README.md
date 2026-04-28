# Two Sum Problem

## Problem
Given an array of integers and a target, return indices of two numbers such that they add up to the target.

## Approach
- Use a hash map (unordered_map)
- Store number → index
- While iterating, check if (target - current element) already exists

## Example
Input: nums = [2, 7, 11, 15], target = 9  
Output: [0, 1]

## Time Complexity
O(n)

## Space Complexity
O(n)