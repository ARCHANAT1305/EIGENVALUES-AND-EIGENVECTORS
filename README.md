# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
prepare the lists from the eigen values and eigen vectors and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
1. import numpy as np
2. a= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
3. values,vectors =  np.linalg.eig(a)
4. print("Eigen values are {} and Eigen vectors are {}".format(values,vectors))

## Output:
![eigen value and vector](https://github.com/ARCHANAT1305/EIGENVALUES-AND-EIGENVECTORS/assets/145975189/8274eeeb-3180-45b2-8d8c-50d379efe4a5)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
