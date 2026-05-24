# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
Python
# Register No: 212225040152 
# Developed By: Jerrin Jose J
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A, 1)
print("%.2f" % norm)

# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A, 2)
print("%.2f" % norm)

# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A, np.inf)
print("%.2f" % norm)






```
## Output:
### 1-Norm of a Matrix
<img width="688" height="402" alt="image" src="https://github.com/user-attachments/assets/919c12eb-af4a-4c56-af9c-2d27c83188f4" />


### 2-Norm of a Matrix
<img width="647" height="421" alt="image" src="https://github.com/user-attachments/assets/23e42d72-5bd5-4c23-8e7b-f963ac89460e" />


### Infinity Norm of a Matrix
<img width="677" height="392" alt="image" src="https://github.com/user-attachments/assets/0e2b8d33-d73b-4a39-98fe-f042e688f106" />
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
