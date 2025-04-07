# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: get the input from user

Step 2: import math and initialise the two values

Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue andsecond is eigenvector) of the given matrix.

Step 4:print the values in format

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Jothi Ganesh P
#RegisterNumber:212224240065
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigenvalues,eigenvectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(eigenvalues,eigenvectors))
```

## Output:
![Screenshot 2025-03-28 081827](https://github.com/user-attachments/assets/6ab97008-798a-4053-8259-c9e6f94346ab)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
