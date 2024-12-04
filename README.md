# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:

#Program to find the eigen values and eigen vectors.

#Developed by: P.Pooja

#RegisterNumber: 24900687


import numpy as np

a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])

values,vectors=np.linalg.eig(a)

print("Eigen values are {} and Eigen Vectors are {} ".format(values,vectors))

## Output:

![Screenshot 2024-12-04 135145](https://github.com/user-attachments/assets/76443829-216b-4552-99c1-2b788aa16397)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
