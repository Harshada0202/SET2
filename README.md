# SET2

## Solution for the given problem statements

**Problem Statement 1**
Write a program to add two lists index-wise. Create a new list that contains the 0th index item from both the list, then the 1st index item, and so on till the last element. any leftover items will get added at the end of the new list.

Given:

list1 = ["M", "na", "i", "Ke"]
list2 = ["y", "me", "s", "lly"]

Expected output:

['My', 'name', 'is', 'Kelly']

**Problem Statement 2**
Given a list of numbers. write a program to turn every item of a list into its square.

Given:

numbers = [1, 2, 3, 4, 5, 6, 7]

Expected output:

[1, 4, 9, 16, 25, 36, 49]

**Problem Statement 3**
Given an unsorted list of some elements(may or may not be integers), Find the frequency of each distinct element in the list using a dictionary. 
Example: 
 

Input : [1, 1, 1, 5, 5, 3, 1, 3, 3, 1,
                  4, 4, 4, 2, 2, 2, 2]
Output : 1 : 5
         2 : 4
         3 : 3
         4 : 3
         5 : 2
_Explanation : Here 1 occurs 5 times, 2 
              occurs 4 times and so on..._

**Problem Statement 4**
Given a string S of lower case characters. The task is to check whether a the given string is Heterogram or not. A heterogram is a word, phrase, or sentence in which no letter of the alphabet occurs more than once. Examples:
Hint: (try to use set)

Input : S = "the big dwarf only jumps"
Output : Yes
Each alphabet in the string S is occurred
only once.

Input : S = "dawn of the day" 
Output : No
Since alphabet 'd', 'a' occurred
more than once.