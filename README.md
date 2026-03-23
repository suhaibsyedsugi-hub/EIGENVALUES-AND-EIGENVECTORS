# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: end the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: s syed suhaib
#RegisterNumber:25013757

import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

## Output:
<img width="831" height="140" alt="image" src="https://github.com/user-attachments/assets/c7b2fdb8-8a58-4bc5-aec5-2ef6652803a6" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
