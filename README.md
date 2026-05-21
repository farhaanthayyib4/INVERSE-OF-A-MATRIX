# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: 
### Step 4: 

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: FARHAAN THAYYIB L
#RegisterNumber:212225230069


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a = np.array([[1, 0, 3],
              [-1, 2, -2],
              [2, 3, -1]])

inv = np.linalg.inv(a)

print(inv)
```
## Output:<img width="1290" height="662" alt="image" src="https://github.com/user-attachments/assets/3fc7aee0-c13f-4f88-9541-178d1d0fb228" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

