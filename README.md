# EIGENVALUES-AND-EIGENVECTORS

# Date:06/04/2024

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step1 : 
importing the numpy library
### Step 2: 
define the given matrix A
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print and end the program

## Program:
```
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print('The eigenvalues and eigenvectors for the given matrix is\n',values,vectors)
```











## Output:
![image](https://github.com/divyaanbu-143/EIGENVALUES-AND-EIGENVECTORS/assets/155506447/d67ff04e-785d-4afb-93ac-a19ef9863133)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
