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
# Register No: 212225040459
# Developed By: Tamilarasan R
# 1-Norm of a Matrix

import numpy as np
matrix = eval(input())
A = np.array(matrix)
nor = np.linalg.norm(A,1)
print(f"{nor:.2f}")


# 2-Norm of a Matrix


import numpy as np

# Type your code here
matrix = eval(input())
A = np.array(matrix)
nor = np.linalg.norm(A,2)
print(f"{nor:.2f}")

# Infinity Norm of a Matrix

import numpy as np 
matrix = eval(input())
A = np.array(matrix)
nor = np.linalg.norm(A,np.inf)
print(f"{nor:.2f}")


```
## Output:
### 1-Norm of a Matrix
<img width="882" height="629" alt="image" src="https://github.com/user-attachments/assets/bba9d6f7-2dca-496f-ad49-8d58cc0cc45f" />


### 2-Norm of a Matrix
<img width="834" height="670" alt="image" src="https://github.com/user-attachments/assets/20aa8066-0cf1-422b-9475-bbe65757205f" />


### Infinity Norm of a Matrix
<img width="769" height="624" alt="image" src="https://github.com/user-attachments/assets/8e8f6fbf-9222-49a6-bbf5-3b2ffc48079e" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
