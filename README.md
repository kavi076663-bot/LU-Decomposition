# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

```

## Output:
<img width="1052" height="489" alt="image" src="https://github.com/user-attachments/assets/f1558d21-9770-4457-9d54-843d09e2e110" />
<img width="1120" height="199" alt="image" src="https://github.com/user-attachments/assets/8459cfdb-8a95-409b-a45c-4f03ca864b0c" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

