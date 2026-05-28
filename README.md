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
# Register No: 212225230081
# Developed By: GOPIKA G
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix
#developed by : GOPIKA G
#REG NO : 212225230081

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2}".format(inf_matrix))




```
## Output:
### 1-Norm of a Matrix

<br>
<br>
<br>
<img width="597" height="360" alt="image" src="https://github.com/user-attachments/assets/d526f050-a068-4fb6-b60b-a52e25b56a35" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="580" height="407" alt="image" src="https://github.com/user-attachments/assets/af6fe0cb-85fb-46d1-82cd-88d2b904a75e" />


### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="582" height="371" alt="image" src="https://github.com/user-attachments/assets/215f3297-4dea-412a-84d2-30f91bfee3cd" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
