# Exp-03---Inverse-of-a-matrix
# Name: DEEPADHARSHINI T
# Reg no: 212224230052
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Read the given square matrix. 
### Step 2:Augment the matrix with the identity matrix of the same order. 
### Step 3:Apply row operations to convert the given matrix into the identity matrix.
### Step 4:The transformed identity matrix becomes the inverse of the given matrix.

## Program:
```
import numpy as np

A = np.array([[2, 1, 1],
              [1, 1, 1],
              [1, -1, 2]])
B = np.linalg.inv(A)
print(B)
```
## Output:

<img width="1288" height="243" alt="image" src="https://github.com/user-attachments/assets/cc979a29-ca9c-400e-ac68-4809bcaff03f" />

## Result:
Thus the inverse of given matrix is successfully solved using python program
