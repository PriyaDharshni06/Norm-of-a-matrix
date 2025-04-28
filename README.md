# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
# 1. Get the input matrix using np.array()   
# 2. Find the 2-norm of the matrix using np.linalg.norm()
# 3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:212224100045
# Developed By:PRIYA DHARSHNI S
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 1)
NORM = "{:.2f}".format(ans)
print(NORM)

# 2-Norm of a Matrix

import numpy as np
# Type your code here
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
NORM = "{:.2f}".format(ans)
print(NORM)

# Infinity Norm of a Matrix

import numpy as np
matrix = np.array(eval(input()))
red = np.max(np.sum(np.abs(matrix), axis=1))
print(f"{red:.2f}")

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-28 214418](https://github.com/user-attachments/assets/317028f6-ba66-41ac-aab5-18e576d522f6)


### 2-Norm of a Matrix
![Screenshot 2025-04-28 214433](https://github.com/user-attachments/assets/c29b253f-59c3-45ce-8e09-eda7cafd2943)


### Infinity Norm of a Matrix
![Screenshot 2025-04-28 214556](https://github.com/user-attachments/assets/4f1accfe-a6db-4aec-b7dc-10cd42eff3a5)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
