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
```
import numpy as np


A = np.array([[-2, 2, -3],
              [ 2, 1, -6],
              [-1, -2, 0]])


eigenvalues, eigenvectors = np.linalg.eig(A)


eigenvalues = np.round(eigenvalues, decimals=1)
eigenvectors = np.round(eigenvectors, decimals=8)


print("Eigen values are", eigenvalues,"and","Eigen Vectors are", eigenvectors)
```

## Output:
![Screenshot 2024-11-28 044804](https://github.com/user-attachments/assets/aff58b73-701e-44b2-91a2-b2e9f7003d20)
![Screenshot 2024-11-28 044825](https://github.com/user-attachments/assets/991bc6c3-acd4-4b9c-b5e4-381f502ac1d2)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
