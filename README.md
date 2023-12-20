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
# Register No: P.Jeshwanth Kumar
# Developed By: 212223240114
# 1-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Jeshwanthkumarpayyavula/Norm-of-a-matrix/assets/145742402/13ca6131-76f9-4cfc-bd34-f409ef31130f)

### 2-Norm of a Matrix
![image](https://github.com/Jeshwanthkumarpayyavula/Norm-of-a-matrix/assets/145742402/57f4b39c-b38d-469a-87cb-aff6c83f2800)

### Infinity Norm of a Matrix
![image](https://github.com/Jeshwanthkumarpayyavula/Norm-of-a-matrix/assets/145742402/f0ea5a83-0f24-49c7-be86-f6994a8077cc)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
