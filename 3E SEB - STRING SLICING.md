# Exp.No:3e
## SEB - PATTERN MATCHING USING REGEX

### AIM  
To write a Python program to find sequences of Upper case letters joined with a '@'.

### ALGORITHM

1. Begin the program.  
2. Read a string input from the user and store it in a.
3. Define a function find_match(s) that uses re.fullmatch() to check if the string matches the pattern [a-z]+@[a-z]+.
4. If the pattern matches, print "Found a match!", otherwise print "Not matched!".
Call the function find_match(user_input) and terminate the program.
5. Terminate the program.

### PROGRAM
```
Reg.No: 212223060305
Name: Vishnu Priya E

import re
a=str(input())
pattern=r'[A-Z]+@'
if re.search(pattern,a):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT

### RESULT
