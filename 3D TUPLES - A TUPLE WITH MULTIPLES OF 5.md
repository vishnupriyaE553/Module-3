# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

### PROGRAM
```
N=int(input())
result=[]
for i in range(1,N,1):
    t=5*i
    if t>=N:
        break
    result.append(t)
print(tuple(result))
```
### OUTPUT
<img width="1326" height="301" alt="image" src="https://github.com/user-attachments/assets/00dbbd5a-9487-4dad-96e0-c2b529801bf6" />

### RESULT
Thus a Python program to create a tuple containing all multiples of 5 up to a given number N was executed and implemented successfully.
