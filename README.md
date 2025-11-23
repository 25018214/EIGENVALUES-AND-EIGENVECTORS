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
#Program to find the eigen values and eigen vectors.
#Developed by: Akash A
#RegisterNumber:25018214
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

```

## Output:
<img width="1177" height="767" alt="Screenshot 2025-11-23 090249" src="https://github.com/user-attachments/assets/5577cc3a-dfc1-4535-b504-75a0a802d110" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
