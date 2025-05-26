# Day27-50-days-coding-challenge
Problem 1: Path Sum in a Binary Tree

Given the root of a binary tree and an integer targetSum, determine if the tree has a root-to-leaf path with a sum equal to targetSum.

Approach:
- Use a recursive depth-first search (DFS) to traverse the tree.
- Subtract the current node's value from targetSum at each step.
- If a leaf node is reached and targetSum equals the node's value, return true.
- Handles edge cases like an empty tree or negative node values.

Time Complexity: O(N) where N is the number of nodes in the tree.

Example:
Input: root = [5,4,8,11,null,13,4,7,2,null,null,null,1], targetSum = 22
Output: true

Problem 2: Maximum Subarray Sum (Kadane’s Algorithm)
Find the contiguous subarray with the largest sum.

Approach:
- Use Kadane's Algorithm, a dynamic programming technique.
- Maintain current_sum to keep track of the running subarray sum.
- If current_sum becomes negative, reset it to zero.
- Track the maximum sum encountered during traversal.

Time Complexity: O(n)
Space Complexity: O(1)

Example:
Input: nums = [-2,1,-3,4,-1,2,1,-5,4]
Output: 6

Notes:
- Covers the core concepts of recursive tree traversal and dynamic programming.
- This solution is a part of the #DrGViswanathanChallenge for 50 days of coding.
