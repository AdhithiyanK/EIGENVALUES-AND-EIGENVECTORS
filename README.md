# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
 import math operations
### Step 2: 
make operations in the given matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
 end the program

## Program:
```#Program to find the eigen values and eigen vectors.
#Developed by: Adhithiyan K
#RegisterNumber:22001999
import numpy as np
A=np.array([[2,2],[1,3]])
values,vector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))
```
Output:
![Screenshot_20230122_090028](https://user-images.githubusercontent.com/121029258/213924750-9700da8c-9a0d-4bb9-b915-3e0805dd9c26.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
