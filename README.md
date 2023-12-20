# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Start the program
### Step 2: 
Initiate a varibale to input the matrix using np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Kishore B
#RegisterNumber:23013723

import numpy as np 
m=([2,-3,0],[2,-5,0],[0,0,3])
w,v=np.linalg.eig(m)
print("Eigen values are",w,"and Eigen Vectors are",v)
```

## Output:
![Screenshot from 2023-12-20 20-33-13](https://github.com/codedbykishore/EIGENVALUES-AND-EIGENVECTORS/assets/147139122/b9abebb3-9503-4f4a-a36f-d99e21ce4f95)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
