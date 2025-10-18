# LU Decomposition 
## Developed By:Mirtyunjay.S
## RegisterNumber:212224040190
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4.print the variable 'X' 
## Program:
(i) To find the L and U matrix
```python
/*
Program to find the L and U matrix.
Developed by: Mirtyunjay S
RegisterNumber: 212224040190
import numpy as np
from scipy.linalg import lu
A =np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```python
/*
Program to find the LU Decomposition of a matrix.
Developed by: Mirtyunjay .S
RegisterNumber: 212224040190
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)

*/
```

## Output:
<img width="1237" height="583" alt="Screenshot 2025-10-18 073952" src="https://github.com/user-attachments/assets/1bae3238-6bc7-4a1b-b58c-5104a9bc84cc" />
<img width="1227" height="314" alt="Screenshot 2025-10-18 074010" src="https://github.com/user-attachments/assets/0885a5d5-4d00-4ea0-a6cf-6d7ec554cfcb" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

