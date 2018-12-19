# Go Solution for LeetCode algorithm problems

[![Build Status](https://travis-ci.org/zwfang/leetcode.svg?branch=master)](https://travis-ci.org/zwfang/leetcode)
[![codecov](https://codecov.io/gh/zwfang/leetcode/branch/master/graph/badge.svg)](https://codecov.io/gh/zwfang/leetcode)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/86cf2613fa544ab5b254e2a7e5d9deb8)](https://www.codacy.com/app/zwfang/leetcode?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=zwfang/leetcode&amp;utm_campaign=Badge_Grade)

continually updating 😃.

### [view by sorted](./src/README.md)

### Array
* [1. Two Sum](./src/0001_two_sum/twosum.go)&nbsp;&nbsp;&nbsp;*`lookup table;`*&nbsp;&nbsp;*`hash table`*
* [167. Two Sum II - Input array is sorted](./src/0167_two_sum2/two_sum2.go)&nbsp;&nbsp;&nbsp;*`double index;`*&nbsp;&nbsp;*`binary search`*
* [209. Minimum Size Subarray Sum](./src/0209_minimum_size_subarray_sum/minimum_size_subarray_sum.go)&nbsp;&nbsp;&nbsp;*`sliding window`*
* [283. Move Zeroes(solution1)](./src/0283_move_zeroes/move_zeroes.go)&nbsp;&nbsp;&nbsp;*`sliding window`*
* [283. Move Zeroes(solution2)](./src/0283_move_zeroes/move_zeroes2.go)&nbsp;&nbsp;&nbsp;*`sliding window`*
* [349. Intersection of Two Arrays](./src/0349_intersection_of_2_arrays/intersection_of_two_arrays.go)&nbsp;&nbsp;&nbsp;*`set`*
* [350. Intersection of Two Arrays II](./src/0350_intersection_of_two_arrays2/intersection_of_two_arrays2.go)&nbsp;&nbsp;&nbsp;*`hash table`*
* [447. Number of Boomerangs](./src/0447_number_of_boomerangs/number_of_boomerangs.go)&nbsp;&nbsp;&nbsp;*`hash table`*
* [454. 4Sum II](./src/0454_4sum2/4sum2.go)&nbsp;&nbsp;&nbsp;*`hash table`*
* [747. Largest Number At Least Twice of Others](./src/0747_largest_number_at_least_twice_of_others/largest_number_at_least_twice_of_others.go)

### String
* [3. Longest Substring Without Repeating Characters](./src/0003_longest_substring_without_repeating_characters/longest_substring_without_repeating_characters.go)&nbsp;&nbsp;&nbsp;*`sliding window;`*&nbsp;&nbsp;*`hash table`*
* [17. Letter Combinations of a Phone Number](./src/0017_letter_combination_of_a_phone_number/letter_combination_of_phone_number.go)&nbsp;&nbsp;&nbsp;*`tree`*
* [20. Valid Parentheses](./src/0020_valid_parentheses/valid_parentheses.go)&nbsp;&nbsp;&nbsp;*`stack`*
* [67. Add Binary](./src/0067_add_binary/add_binary.go)&nbsp;&nbsp;&nbsp;*`brute force`*
* [76. Minimum Window Substring](./src/0076_minimum_window_substring/minimum_window_substring.go) &nbsp;&nbsp;&nbsp;*`sliding window`*
* [438. Find All Anagrams in a String](./src/0438_all_anagrams_in_a_string/all_anagrams_in_a_string.go)&nbsp;&nbsp;&nbsp;*`sliding window`*

### Linked List
* [2. Add Two Numbers](./src/0002_add_two_numbers/add_two_numbers.go)&nbsp;&nbsp;&nbsp;*`recursion;`*&nbsp;&nbsp;*`math`*
* [21. Merge Two Sorted Lists](./src/0021_merge_two_sorted_lists/mergeTwoLists.go)
* [25. Reverse Nodes in k-Group](./src/0025_reverse_nodes_in_k_group/reverse_node_k_group.go)
* [61. Rotate List](./src/0061_rotate_list/rotate_list.go)

### Dynamic Programming
* [62. Unique Paths](./src/0062_unique_paths/unique_paths.go)&nbsp;&nbsp;&nbsp;*`array`*
* [63. Unique Paths 2](./src/0063_unique_paths_2/unique_paths2.go)&nbsp;&nbsp;&nbsp;*`array`*
* [64. Minimum Path Sum](./src/0064_minimum_path_sum/minimum_path_sum.go)&nbsp;&nbsp;&nbsp;*`array`*
* [70. Climbing Stairs](./src/0070_climbing_stairs/climbing_stairs.go)
* [120. Triangle](./src/0120_triangle/triangle.go)&nbsp;&nbsp;&nbsp;*`array`*
* [198. House Robber](./src/0198_house_robber/house_robber.go)
* [300. Longest Increasing Subsequence](./src/0300_longest_increasing_subsequence/lis.go)
* [343. Integer Break](./src/0343_integer_break/integer_break.go)&nbsp;&nbsp;&nbsp;*`math`*
* [376. Wiggle Subsequence](./src/0376_wiggle_subsequence/wiggle_subsequence.go)&nbsp;&nbsp;&nbsp;*`greedy;`*&nbsp;&nbsp;*`dynamic programming`*
* [416. Partition Equal Subset Sum](./src/0416_partition_equal_subset_sum/partition_equal_subset_sum.go)&nbsp;&nbsp;*`0-1 knapsack problem`*
* [435. Non-overlapping Intervals](./src/0435_non_overlapping_intervals/dp_solution.go)&nbsp;&nbsp;&nbsp;*`greedy;`*&nbsp;&nbsp;*`dynamic programming`*&nbsp;&nbsp;*`0-1 knapsack problem`*

### Greedy
* [392. Is Subsequence](./src/0392_is_subsequence/is_subsequence.go)
* [435. Non-overlapping Intervals](./src/0435_non_overlapping_intervals/greedy_solution.go)&nbsp;&nbsp;&nbsp;*`greedy;`*&nbsp;&nbsp;*`dynamic programming`*
* [455. Assign Cookies](./src/0455_assign_cookies/assign_cookies.go)

### Binary Tree
* [94. Binary Tree Inorder Traversal](./src/0094_binary_tree_inorder_traversal/binary_tree_inorder_traversal.go)&nbsp;&nbsp;&nbsp;*`stack`*
* [100. Same Tree](./src/0100_same_tree/same_tree.go)&nbsp;&nbsp;&nbsp;*`dfs`*
* [101. Symmetric Tree](./src/0101_symmetric_tree/symmetric_tree.go)&nbsp;&nbsp;&nbsp;*`dfs;`*&nbsp;&nbsp;*`bfs;`*
* [107. Binary Tree Level Order Traversal II](./src/0107_binary_tree_level_order_traversal_2/binary_tree_level_order_traversal2.go)&nbsp;&nbsp;&nbsp;*`bfs`*
* [111. Minimum Depth of Binary Tree](./src/0111_minimum_depth_of_binary_tree/minimum_depth_of_binary_tree.go)&nbsp;&nbsp;&nbsp;*`dfs`*
* [112. Path Sum](./src/0112_path_sum/path_sum.go)&nbsp;&nbsp;&nbsp;*`dfs`*
* [226. Invert Binary Tree](./src/0226_invert_binary_tree/invert_binary_tree.go)

### Binary Search
* [704. Binary Search](./src/0704_binary_search/binary_search.go)

<details>
</details>
