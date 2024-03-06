# smallest-free-number
A coding challenge to find the smallest non-negative integer that is not part of a given set of non-negative integers.

Thanks to [Nicolas Rinaudo](https://github.com/abcoates/smallest-free-number.git) for suggesting this problem for a coding challenge.

## Description
This is a simplification a general problem, find the 'least XXX' object that is not already used, where 'XXX' is some arbitrary measurement dimension such as 'large', 'expensive', etc.

In this minimal version, you are given a set (i.e. an **unordered** set) of non-negative integers, and you have to find the smallest integer that is **not** a part of the set.

## Examples
 * \[0, 1, 2, 3, 5\] => 4
 * \[2, 1, 0\] => 3
 * \[20, 10, 30\] => 0

## Special Note
You **may** use AI to help you write the code.  As AI coding companions are inevitable, we might as well all start practicising how to use them.  **However**, if you have used AI to help you write your code, please make that clear in your solution.

## Stretch Goal
Finding a solution is straightforward, but can you find a solution that only takes linear time?  Measure how the time taken for your solution varies as the size of the set is increased, and see how close you can get to the time taken growing linearly with the size of the set.  Create a graph of the time measurements again set size.

You will need to generate unordered sets of numbers that are sufficiently large to make the solution time sufficiently measurable.

Your results may vary with the **density** of the sets, i.e. with the percentage of unused numbers in the range from zero to the largest number in the set.