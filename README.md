# LU Decomposition 
## Name: Harini P
## Register Number: 212224230082

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Import required libraries (NumPy and SciPy) and read the input matrix A.

## Step 2:
Perform LU decomposition of matrix A and obtain L and U matrices.

## Step 3:
Display the L and U matrices to verify the decomposition.

## Step 4:
If required, read matrix/vector B and solve the system AX = B using LU factorization.

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot= lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:

<img width="1287" height="522" alt="image" src="https://github.com/user-attachments/assets/a8d7c407-e614-40be-bc73-e591faeefc83" />
<img width="1251" height="284" alt="image" src="https://github.com/user-attachments/assets/491dc673-eab9-4521-ad77-4bea5362b796" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
