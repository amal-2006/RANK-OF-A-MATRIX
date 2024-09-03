## DATE:
## EX 2 - RANK OF A MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each equation and assign in np.array   
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
```



#Program to find the rank of a matrix.
#Developed by: AMALJOSH MAADHAV J
#RegisterNumber:212223230012



import numpy as np
A =  [[5,3,-10],[2,2,-3],[-3,1,5]]
B = np.linalg.matrix_rank(A)
print(B)





```
## Output:
![Screenshot 2024-09-03 085326](https://github.com/user-attachments/assets/db46bf56-49d6-4ac4-9ebe-3d447f62aa27)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

