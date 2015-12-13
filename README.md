This lab will give you an opportunity to practice your skills solving problems with Strings.

Remember no matter what programming langugage you use, the following top level methods are available:
+ extract char from string at particular index
+ extract string substring
+ equality, length, to character array
+ sort, type convert from integer to string and vice versa

### Lab 1
**Reverse words in a string**

Given an input string, reverse the string word by word.
For example, given s = "the grass is green", return "green is grass the".

**Length of Last Word**

Given a string s consists of upper/lower-case alphabets and empty space characters ' ', return the length of last word in the string. If the last word does not exist, return 0.

### Lab 2
**Isomorphic Strings**

Given two strings s and t, determine if they are isomorphic. Two strings are isomorphic if the characters in s can be replaced to get t.
For example,"egg" and "add" are isomorphic, "foo" and "bar" are not.

**String Palindrome**

A string is a palindrome if it remains unchanged when reversed, for example "dad" is a palindrome as reverse of "dad" is "dad" whereas "program" is not a palindrome. Some other palindrome strings are "mom", "civic", "madam".

**Word Ladder** -- Extra Credit
Given two words (start and end), and a dictionary, find the length of shortest transformation sequence from start to end, such that only one letter can be changed at a time and each intermediate word must exist in the dictionary. For example, given:
```
start = "hit"
end = "cog"
dict = ["hot","dot","dog","lot","log"]
One shortest transformation is "hit" -> "hot" -> "dot" -> "dog" -> "cog", the program should return its length 5.
```

### Lab 3
This lab will give you an opportunity to practice your skills solving problems with Arrays.

**Two Sum **
Given an array of integers, find two numbers such that they add up to a specific target number.

The function twoSum should return indices of the two numbers such that they add up to the target, where index1 must be less than index2. Please note that your returned answers (both index1 and index2) are not zero-based.
```
Input: numbers={2, 7, 11, 15}, target=9
Output: index1=1, index2=2
```
**Three Sum**
Given an array S of n integers, are there elements a, b, c in S such that a + b + c = 0? Find all unique triplets in the array which gives the sum of zero.
```
For example, given array S = {-1 0 1 2 -1 -4},

A solution set is:
(-1, 0, 1)
(-1, -1, 2).
    
Note:
Elements in a triplet (a,b,c) must be in non-descending order. (ie, a ≤ b ≤ c)
The solution set must not contain duplicate triplets.
```

### Lab 4
**K-th largest element in array**
Find the kth largest element in an unsorted array. Note that it is the kth largest element in the sorted order, not the kth distinct element.
```
For example, given [3,2,1,5,6,4] and k = 2, return 5.

Note: You may assume k is always valid, 1 ≤ k ≤ array's length.
```

**Contains Duplicate**
Given an array of integers, find if the array contains any duplicates. Your function should return true if any value appears at least twice in the array, and it should return false if every element is distinct.

###Extra Credit
Given an array of integers and an integer k, return true if and only if there are two distinct indices i and j in the array such that nums[i] = nums[j] and the difference between i and j is at most k.

### Lab 5
**Median of two sorted arrays**
There are two sorted arrays A and B of size m and n respectively. Find the median of the two sorted arrays. 

**Minimum size subarray size**

Given an array of n positive integers and a positive integer s, find the minimal length of a subarray of which the sum ≥ s. If there isn't one, return 0 instead.

```
For example, given the array [2,3,1,2,4,3] and s = 7, the subarray [4,3] has the minimal length of 2 under the problem constraint.
```

This lab will give you an opportunity to practice your skills solving problems with Math.
### Lab 6
**Power function**
Implement pow(x, n).

**Count Primes**
Count the number of prime numbers less than a non-negative number, n.

** Reverse Integer**
```
Reverse digits of an integer.
Example1: x = 123, return 321
Example2: x = -123, return -321
```
Extra Credit
**Subsets**
Given a set of distinct integers, S, return all possible subsets.
```
For example, given S = [1,2,3], the method returns:
[
  [3],
  [1],
  [2],
  [1,2,3],
  [1,3],
  [2,3],
  [1,2],
  []
]
```
 
This lab will give you an opportunity to practice your skills solving problems with Linked List.


This lab will give you an opportunity to practice your skills solving problems with Algorithms.

### Lab 7
**Print patterns of stars**
```
    *
   ***
  *****
 *******
*********
```

**Print patterns of letters & stars**
```
   *
  *A*
 *A*A*
*A*A*A*
```

Extra Credit
```
        1
       232
      34543
     4567654
    567898765
```

### Lab 8
**Given a linked list, determine if it has a cycle in it.**
If we have 2 pointers - fast and slow. It is guaranteed that the fast one will meet the slow one if there exists a circle.

**Merge Lists**
Merge two sorted linked lists and return it as a new list. The new list should be made by splicing together the nodes of the first two lists.

### Lab 9
**LRU**
Design and implement a data structure for Least Recently Used (LRU) cache. It should support the following operations: get and set.

```
get(key) - Get the value (will always be positive) of the key if the key exists in the cache, otherwise return -1.
set(key, value) - Set or insert the value if the key is not already present. When the cache reached its capacity, it should invalidate the least recently used item before inserting a new item.
```
