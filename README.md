# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
We have imported numpy which is needed.
### Step 2: 
We have created a matrix by using np.array with different values in it.
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
Finally, print the value of the rank of the matrix.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: MAHESWARAN.K
#RegisterNumber: 212222110023

import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![m2pdf](https://user-images.githubusercontent.com/119478181/225951438-46320643-6624-4c53-b367-c1118f42b470.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

