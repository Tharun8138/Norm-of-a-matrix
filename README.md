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
# Register No: 212224230290
# Developed By: THARUN.V

# 1-Norm of a Matrix :

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix :

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix :

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-05-13 142326](https://github.com/user-attachments/assets/def2e714-839f-4e48-be81-2bfcb94f0d91)


### 2-Norm of a Matrix
![Screenshot 2025-05-13 142422](https://github.com/user-attachments/assets/59717ca7-df53-4979-a6c5-5e8ba2a7ace9)


### 3-Infinity Norm of a Matrix
![Screenshot 2025-05-13 142450](https://github.com/user-attachments/assets/48af9d26-284b-41f5-9ffb-920e3dcdff6d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
