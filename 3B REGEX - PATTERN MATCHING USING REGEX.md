# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

### AIM  
Write a Python program to find sequences of Upper case letters joined with a underscore.

### ALGORITHM

1. Begin the program.  
2. Accept a string `a` from the user.  
3. Define the regular expression pattern as `r'[A-Z]+_'`.  
4. Use the `re.search()` function to check if the string `a` is found in the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

### PROGRAM
```
reg.no: 212223060305
name: Vishnu Priya E

import re
a=input()
pattern=r'[A-Z]+_'
if re.search(pattern,a):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
<img width="939" height="303" alt="image" src="https://github.com/user-attachments/assets/2ebb8e78-4248-4982-bd22-7e04ae7da9da" />

### RESULT
Thus a Python program using regular expressions was executed and implemented successfully.
