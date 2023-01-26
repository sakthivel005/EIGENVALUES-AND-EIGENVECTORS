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
Prepare a list for each linear equation and assign in numpy.linalg()

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
Print the eigen value and eigen vector using print() function.End the program

## Program:
```
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

```

## Output:

![Screenshot from 2023-01-26 14-07-01](https://user-images.githubusercontent.com/120550359/214825511-f4ff6d82-433d-4527-9fff-6755308cfee7.png) ![Screenshot from 2023-01-26 14-07-21](https://user-images.githubusercontent.com/120550359/214825568-e79a92c4-3d51-4925-9071-0ec527fa2ebe.png)



 



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
