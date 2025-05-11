# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the NumPy module using import numpy as np to perform matrix and norm calculations.
### Step 2:
Get the input matrix using  np.array()   
### Step 3:
Use the np.linalg.norm() function to compute:
1-norm by setting ord=1
2-norm by setting ord=2
Infinity norm by setting ord=np.inf
### Step 4:
Print the norm of the matrix in two decimal places.
### Step 5:
End the program.
## Program:
```Python
# Register No:212224100007
# Developed By:Buvaneshwari R
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
result=np.linalg.norm(a,1)
print(result)

# 2-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))

# Infinity Norm of a Matrix
import numpy as np
matrix =np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))

```
## Output:
### 1-Norm of a Matrix
![alt text](<Screenshot 2025-05-11 185035.png>)

### 2-Norm of a Matrix
![alt text](<Screenshot 2025-05-11 185118.png>)

### Infinity Norm of a Matrix
![alt text](<Screenshot 2025-05-11 185154.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
