# 📌 Two Pointers & Sliding Window Complete Guide (With LeetCode Links)

Welcome to the complete guide to mastering **Two Pointers** and **Sliding Window** techniques — two of the most essential patterns for solving array and string problems efficiently.

---

## 🔍 What is Two Pointers?

### ✅ Concept:

Two pointers is a technique where you use two variables (often called `left` and `right`) to iterate over an array or string, usually from both ends or starting at different positions.

### ✅ When to Use:

* When the input is **sorted** (e.g., for sum, duplicates, pairs)
* When solving **palindrome**, **linked list**, or **array traversal** problems
* When looking for **pairs/triplets/subarrays** that meet a certain condition

### ✅ Common Use Cases:

* Finding pairs that sum to a target
* Removing duplicates in-place
* Palindrome checks
* Merging arrays

---

## 🚀 Two Pointers LeetCode Questions

| # | Problem                             | Link                                                                       |
| - | ----------------------------------- | -------------------------------------------------------------------------- |
| 1 | Two Sum II – Input Array is Sorted  | [Link](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)    |
| 2 | Container With Most Water           | [Link](https://leetcode.com/problems/container-with-most-water/)           |
| 3 | 3Sum                                | [Link](https://leetcode.com/problems/3sum/)                                |
| 4 | 4Sum                                | [Link](https://leetcode.com/problems/4sum/)                                |
| 5 | Merge Sorted Array                  | [Link](https://leetcode.com/problems/merge-sorted-array/)                  |
| 6 | Remove Duplicates from Sorted Array | [Link](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) |
| 7 | Valid Palindrome                    | [Link](https://leetcode.com/problems/valid-palindrome/)                    |
| 8 | Linked List Cycle II (fast/slow)    | [Link](https://leetcode.com/problems/linked-list-cycle-ii/)                |

---

## 🌊 What is Sliding Window?

### ✅ Concept:

Sliding Window is a technique where you maintain a **subarray or substring** that satisfies a condition and **slide the window** by changing its start and end.

### ✅ When to Use:

* When dealing with **subarrays**, **substrings**, or **fixed/variable window problems**
* When optimizing brute-force approaches with nested loops

### ✅ Types:

1. **Fixed-Size Window** — Window size is constant (e.g., max average subarray of size K)
2. **Variable-Size Window** — Expand/shrink the window based on constraints

---

## 🚀 Sliding Window LeetCode Questions

### 📏 Fixed-size Window

| # | Problem                                             | Link                                                                                                                 |
| - | --------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| 1 | Maximum Average Subarray I                          | [Link](https://leetcode.com/problems/maximum-average-subarray-i/)                                                    |
| 2 | Number of Sub-arrays of Size K and Avg >= Threshold | [Link](https://leetcode.com/problems/number-of-sub-arrays-of-size-k-and-average-greater-than-or-equal-to-threshold/) |
| 3 | Substrings of Size Three with Distinct Characters   | [Link](https://leetcode.com/problems/substrings-of-size-three-with-distinct-characters/)                             |
| 4 | Sliding Window Maximum                              | [Link](https://leetcode.com/problems/sliding-window-maximum/)                                                        |
| 5 | Find All Anagrams in a String                       | [Link](https://leetcode.com/problems/find-all-anagrams-in-a-string/)                                                 |
| 6 | Permutation in String                               | [Link](https://leetcode.com/problems/permutation-in-string/)                                                         |

### 📐 Variable-size Window

| # | Problem                                        | Link                                                                                  |
| - | ---------------------------------------------- | ------------------------------------------------------------------------------------- |
| 1 | Minimum Size Subarray Sum                      | [Link](https://leetcode.com/problems/minimum-size-subarray-sum/)                      |
| 2 | Longest Substring Without Repeating Characters | [Link](https://leetcode.com/problems/longest-substring-without-repeating-characters/) |
| 3 | Longest Repeating Character Replacement        | [Link](https://leetcode.com/problems/longest-repeating-character-replacement/)        |
| 4 | Max Consecutive Ones III                       | [Link](https://leetcode.com/problems/max-consecutive-ones-iii/)                       |
| 5 | Fruit Into Baskets                             | [Link](https://leetcode.com/problems/fruit-into-baskets/)                             |
| 6 | Subarray Product Less Than K                   | [Link](https://leetcode.com/problems/subarray-product-less-than-k/)                   |
| 7 | Count Number of Nice Subarrays                 | [Link](https://leetcode.com/problems/count-number-of-nice-subarrays/)                 |

---

## ✅ How to Approach These Patterns

### For Two Pointers:

1. Try brute-force first
2. Check if array is sorted
3. Maintain two indices and think of shrinking or moving both ends
4. Think of fast & slow pointers for linked list problems

### For Sliding Window:

1. Define the window: what should be inside it?
2. Try brute-force nested loop → then optimize by sliding window
3. Use a map or counter for frequency tracking
4. Shrink the window when condition breaks

---

## 📚 Final Tips

* Use **dry run** on paper to understand pointer movement
* Practice **Edge Cases**: empty arrays, large input, duplicates, negatives
* Solve 3–5 questions from each category first, then move to harder ones

---

## ✍️ Author

**Saurabh Singh**
🔗 [GitHub](https://github.com/saurabhxcod)

> "Pointers and Windows are how you move through problems. Learn to walk before you run."

Happy Solving! 💪
