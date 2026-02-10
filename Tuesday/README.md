# 📅 Tuesday

## 1. Write a Static Generic Method called removeDuplicates.
- The Method Signature: public static <T> ArrayList<T> removeDuplicates(ArrayList<T> list)
- The Goal: Take an ArrayList of any type (Strings, Integers, or your Car objects from the Parking project) and return a new ArrayList that contains no duplicates.

## 2. Look closely at the removeDuplicates method you just wrote.
- Question A: If you used a nested loop (a loop inside a loop) to check for duplicates, what is the Big O complexity?
- Question B: If the input list has 1,000,000 items, why would the nested loop version potentially crash or hang the computer?
- Question C: How does the performance change if the input list is already sorted?

## 3. Write a method hasTargetSum(int[] nums, int target) that returns true if any two numbers in the array add up to the target.
- You could write it using nested loops (O(n^2)).
- In a comment, describe how you could solve this faster if the array was already sorted. Could you do it by looking at both ends of the array and moving toward the middle? What would that Big O be?
