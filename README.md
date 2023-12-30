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
# Register No: 212223230250
# Developed By: V. Yogesh
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
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-30 142155](https://github.com/Yogesh-Yogi-1/Norm-of-a-matrix/assets/148514598/351d1cdb-f8d7-4e40-84c8-21ad3c753f80)

<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot 2023-12-30 142218](https://github.com/Yogesh-Yogi-1/Norm-of-a-matrix/assets/148514598/429743c9-be2d-460d-a765-a990441705fc)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot 2023-12-30 142235](https://github.com/Yogesh-Yogi-1/Norm-of-a-matrix/assets/148514598/7ee55657-8084-426f-92cf-a591c8f829cd)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
