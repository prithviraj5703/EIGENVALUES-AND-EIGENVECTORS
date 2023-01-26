# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpy as np
### Step 2: 
arrange the given matrix in np.array command
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
run the program and get the output
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: mithra mukundaa
#RegisterNumber:22005703
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and","Eigen Vectors are",vectors)
```
## Output:
![eigen values and eigen vectors](https://user-images.githubusercontent.com/121418418/214910787-7d275849-b1c5-495d-b8f1-7406bde315b5.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
