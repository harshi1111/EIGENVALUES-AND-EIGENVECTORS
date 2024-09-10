# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the Numpy Library.
### Step 2: Assign the matirx value.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the values.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: HARSHITHA V
#RegisterNumber:212223230074
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
b,c=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(b,c))
```
## Output:
![image](https://github.com/user-attachments/assets/fe9c5b93-e63f-4abc-8b2b-086569547cdd)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
