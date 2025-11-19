# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import required libraries numpy and scipy.linalg.
2. Input the matrix/matrices using eval(input()).
3. Perform LU decomposition using lu() or solve equations using lu_factor() and lu_solve().
4. Print the results L and U matrices or solution X matrix.

## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: MUTHUAKASH M
#RegisterNumber: 25016467
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
#Program to solve a matrix using LU decomposition.
#Developed by: MUTHUAKASH M
#RegisterNumber: 25016467
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
```

## Output:
(i) To find the L and U matrix 
<img width="1222" height="803" alt="image" src="https://github.com/user-attachments/assets/78005edf-cd45-4f4c-a5a2-98250f5df545" />
(ii) To find the LU Decomposition of a matrix
<img width="1227" height="710" alt="image" src="https://github.com/user-attachments/assets/e8b88dbb-2d9c-4838-941f-5f4bc3b75873" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

