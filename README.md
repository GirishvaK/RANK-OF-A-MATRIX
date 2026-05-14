# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
#Program to find the rank of a matrix.
#Developed by: Girishva.K
#RegisterNumber: 212225040094
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:

<img width="1280" height="862" alt="image" src="https://github.com/user-attachments/assets/c5b6c977-d4a9-4bb3-a3eb-0ffb0e2ee280" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

