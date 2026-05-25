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
# Register No:212225040310
# Developed By:PRAGATHEESWARAN K
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,1)
print(f"{norm:.2f}")
# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,2)
print(f"{norm:.2f}")
# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,np.inf)
print(f"{norm:.2f}")
```
## Output:
### 1-Norm of a Matrix
<br>
<img width="1273" height="746" alt="image" src="https://github.com/user-attachments/assets/bef66299-de35-4059-8ab4-974ba392b893" />
<br>
### 2-Norm of a Matrix
<br>
<img width="1238" height="871" alt="image" src="https://github.com/user-attachments/assets/edc1dea2-45c7-42a3-9a95-4af1ed452315" />
<br>

### Infinity Norm of a Matrix
<br>
<img width="1345" height="844" alt="image" src="https://github.com/user-attachments/assets/0c8b994c-1f50-4e62-a7fa-b99ef2018b2b" />
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
