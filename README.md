# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Prepare the list for each linear equation and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: kishore N
#RegisterNumber:212223230106
import numpy as np
matrix=np.array([[2,2],[1,3]])
eigval,eigvect=np.linalg.eig(matrix)
print("Eigen values are",eigval,"and Eigen Vectors are",eigvect)
```
## Output:
![Screenshot 2024-04-15 214649](https://github.com/kishorenagarajan08/EIGENVALUES-AND-EIGENVECTORS/assets/155753188/23476f83-6cf1-4e5e-b6ff-315526eb5dcc)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
