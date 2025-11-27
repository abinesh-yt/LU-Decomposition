# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Input matrix dimensions and initialize augmented matrix and solution vector.

2.Populate the augmented matrix with user inputs.

3.Perform Gaussian elimination to reduce the matrix to upper triangular form, ensuring no division by zero.

4.Back substitute to compute solution values for the variables.

5.Print the solution vector formatted to two decimal places.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Abinesh A
RegisterNumber: 25017255

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Abinesh A
RegisterNumber:25017255
*/
import numpy as np 
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
```

## Output:
<img width="811" height="296" alt="image" src="https://github.com/user-attachments/assets/35d34c63-b73b-439e-ba3e-b5a6bd30c70b" />
<img width="1331" height="217" alt="image" src="https://github.com/user-attachments/assets/35c662d1-5da9-47e1-8abc-3bbd417861e3" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

