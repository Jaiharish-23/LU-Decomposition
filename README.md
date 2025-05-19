# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: Input the coefficient matrix A and the right-hand side vector b.
##3 Step 2: Perform LU decomposition using lu_factor(A) to get LU matrix and pivot indices.
### Step 3: Use lu_solve((lu, piv), b) to solve the system Ax = b.
### Step 4: Print the solution vector x.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: JAI HARISH R
RegisterNumber:212224040124
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: JAI HARISH R
RegisterNumber: 212224040124
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
(i) To find the L and U matrix

![screencapture-lms2-ai-saveetha-in-mod-quiz-review-php-2025-05-19-21_27_00 (1)](https://github.com/user-attachments/assets/d0502427-9a87-4f0c-b58a-7a641f610c7f)


(ii) To find the LU Decomposition of a matrix


![screencapture-lms2-ai-saveetha-in-mod-quiz-review-php-2025-05-19-21_27_00](https://github.com/user-attachments/assets/185640d6-dcb5-40b2-9525-e56c0cfa8c89)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

