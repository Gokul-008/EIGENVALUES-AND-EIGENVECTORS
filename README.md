# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as any variable
### Step 2: 
Let assume any variable
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
Print eigen values and eigen vectors 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Gokul.M
#RegisterNumber:22009089
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Eigen values](https://user-images.githubusercontent.com/121165996/215260617-86b0dd9e-66e6-4dc6-9da1-3971c953270d.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
