# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : importing numpy function
### Step 2: assingning values to the variable in list form
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the eigen values and eigen vectors using print function

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: DEVA ABISHEK P
#RegisterNumber:23012976
import numpy as np
a=[-2,2,-3],[2,1,-6],[-1,-2,0]
b,c=np.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",c)
```


## Output:
![Screenshot 2023-12-12 112755](https://github.com/DEVAABISHEK/EIGENVALUES-AND-EIGENVECTORS/assets/150319305/ed64b243-be23-4657-b522-03df255c4872)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
