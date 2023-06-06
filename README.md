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
```
# Register No:212222240070
# Developed By:NAVEEN S

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)
```
## Output:
### 1-Norm of a Matrix
![ex7(a)](https://github.com/Naveensrinivasan07/Norm-of-a-matrix/assets/119475891/89a24163-f40c-4abe-ba9f-4c0ed2c76fbd)

### 2-Norm of a Matrix
![ex7(b)](https://github.com/Naveensrinivasan07/Norm-of-a-matrix/assets/119475891/0b51c780-0d9d-4077-9cf0-91b1e5bd517e)

### Infinity Norm of a Matrix
![ex7(c)](https://github.com/Naveensrinivasan07/Norm-of-a-matrix/assets/119475891/b5b4e2b6-7964-4de3-ba1c-92770727c05c)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified
