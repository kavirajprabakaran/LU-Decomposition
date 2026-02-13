# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program

## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by:KAVIRAJ.P
RegisterNumber:25017431
'''
import numpy as np
from scipy.linalg import lu
InputMatrix=np.array(eval(input()),dtype='i')
piv,Lmatrix,Umatrix=lu(InputMatrix)
print(Lmatrix)
print(Umatrix)
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by:KAVIRAJ.P
RegisterNumber: 25017431
'''
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
AMatrix=np.array(eval(input()),dtype='i')
BMatrix=np.array(eval(input()),dtype='i')
XMatrix=lu_factor(AMatrix)
solution=lu_solve(XMatrix,BMatrix)
print(solution)
```

## Output:
<img width="814" height="627" alt="Screenshot 2026-02-13 093341" src="https://github.com/user-attachments/assets/396b3ba0-6e2d-46b5-99f4-d880e14d628e" />

<img width="834" height="624" alt="Screenshot 2026-02-13 093406" src="https://github.com/user-attachments/assets/eff2979e-122c-433d-abf5-7bad45402e81" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

