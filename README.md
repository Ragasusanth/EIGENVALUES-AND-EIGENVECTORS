# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start th program

### Step 2: Import the NumPy library for numerical operations.

### Step 3:  Use np.linalg.eig() to compute the eigenvalues and eigenvectors.
             1)This function returns two results:
             2)The first is a 1D array of eigenvalues.
             3)The second is a 2D array where each column is an eigenvector.
             
### Step 4: Display the computed eigenvalues and eigenvectors.


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: RAGA SUSANTH
#RegisterNumber: 212224230217

import numpy as np
a = np.array([[2, 2], [1, 3]])
eig_value,eig_vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_value,eig_vector))
```
## Output:
![image](https://github.com/user-attachments/assets/d003c7e1-b973-44bb-ac2a-2dcb041c318b)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
