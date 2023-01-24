# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy libraray to calculate linear algebric eqauations.
### Step 2:Enter the given given matrix.
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the Eigen values and Eigen vectors.
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: R Guruprasad 
#RegisterNumber:22006697
import numpy as np
a=np.array([[4,2],[2,4]])
val,vec=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(val,vec))
```

## Output:
![eigen](/eigen.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
