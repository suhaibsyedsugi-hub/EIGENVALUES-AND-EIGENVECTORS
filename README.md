# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
import numpy as np

# Define the matrix
A = np.array([
    [2, -3, 0],
    [2, -5, 0],
    [0, 0, 3]
])

# Calculate eigenvalues and eigenvectors
vals, vecs = np.linalg.eig(A)

# Format the output to match your requirement
print(f"Eigen values are {vals} and Eigen Vectors are {vecs}")

## Output:

<img width="1240" height="433" alt="image" src="https://github.com/user-attachments/assets/d8d31e16-2cb4-42e6-b41d-43c73c696268" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
