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
```
#Program to find the eigen values and eigen vectors.
#Developed by: Joel John Jobinse
#RegisterNumber: 23008174
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![maths-exp3](https://github.com/joeljohnjobinse/EIGENVALUES-AND-EIGENVECTORS/assets/138955488/2973bcac-1a4a-4409-ad07-bcc7ebab606a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
