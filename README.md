At first, the function checks if both strings have the same length. If not then they cannot be anagrams. 
For each character in the first string, it searches for the same character in the second string.
If any character matches with the secondf string, it is marked as used replacing it with * so that it wont be matched again.
If any letter of the first string is not found in the second string, then it cannot be anagram so the function immediately returns false.
If all the characters of the first string is matched with the characters of the second string, the they are anagrams, so the the function returns true.

Compkexity
time- O(n^3)
space- O(1)
