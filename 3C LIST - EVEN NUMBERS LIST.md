# Exp.No:3c
## LIST - SUM LIST

### AIM  
To write a Python function that accepts a number N and creates a list containing all even numbers up to N.

### ALGORITHM

1. Begin the program.  
2.Read an integer input n from the user.

3. Define a function createlist(n) that:
      Initializes an empty list l.
      Uses a for loop from 12 to n-1.
      Appends even numbers to the list l.
4. Print the list l and the sum of its elements using sum(l). 
5. Terminate the program.

### PROGRAM
```
Reg.No: 212223060305
Name: Vishnu Priya E

def createlist(n):
    l=[]
    for i in range(12, n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list", sum(l))
```

### OUTPUT
<img width="683" height="217" alt="image" src="https://github.com/user-attachments/assets/f32cd159-2813-4592-bf33-0ae11903d1bd" />

### RESULT
Thus a Python function that accepts a number N and creates a list containing all even numbers up to N was executed and implemented successfully.
