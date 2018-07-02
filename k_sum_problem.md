# Two Sum Problem

This is a famous algorithm interview question: Two Sum. A general description (citing from Leetcode) is:

Given an array of integers, return indices of the two numbers such that they add up to a specific target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

Example:
```
Given nums = [2, 7, 11, 15], target = 9,

Because nums[0] + nums[1] = 2 + 7 = 9,
return [0, 1].
```

This is a fairly straightforward interview question. With some critical thinking, one probably ensd up with a solution using a hash table. 
Regardless of the underlying implementation, what a hash table offers is constant time of insertion and lookup. By compromising the space complexity, we achieve O(n) to scan the list and find the answer.

Simple, huh? Here we will focus how one gets to that point. Or in other words, how human thought process evolves with this simple problem.

The problem has many facets, or say "dimensions": "two" sum gives k = 2 as a dimension and size = n of the list gives another. A general technique of human approaching problems is "Dimension Reduction". You may not notice that often, but you are repeating this on a daily basis. When we are struggled finding the optimal solution of "two sum" problem, we will try to attack 
