# PythonCheatSheetDS
Python Cheatsheet for Data structures
Zip:
The zip() function combines elements from two or more iterables (like lists, tuples, or sets) into tuples, where each tuple contains one element from each iterable.

1. Combine Two Lists or Dictionaries
Example:
s1 = {2, 3, 1}
s2 = {'b', 'a', 'c'}
result = list(zip(s1, s2)) #here s1 is tuple so it is taking in arbitary manar
print(result)  # Output: [(1, 'a'), (2, 'c'), (3, 'b')]
