# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import the Numpy library in your python script
### Step 2: 
Define your matrix for which you want to find the eigenvalues and eigenvectors
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Yashvanth K
#RegisterNumber:23011613
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:

![Screenshot 2024-01-02 170305](https://github.com/Yashvanth21/EIGENVALUES-AND-EIGENVECTORS/assets/144979957/c076e566-7f5d-4a31-96c0-b9d5cef678d1)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
