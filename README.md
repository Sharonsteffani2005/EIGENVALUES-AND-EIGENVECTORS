# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.

### Step 2: Prepare the lists from each equations and assign in np.array()

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### STEP 4: End the program.

NAME: SHARON STEFFANI.F

REG NO:212223110049

DEP:CSE(IOT)

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SHARON STEFFANI.F
#RegisterNumber:212223110049
import numpy as np
A = np.array([[4,2],[2,4]])
values, vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![alt text](<Screenshot 2024-04-10 231311-1.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
