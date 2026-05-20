# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:
Import the numpy module to use the built-in function for calculation.

Step 2:
Prepare the lists from each linear equations and assign in np.array0.

Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

Step 4:
End the program.

## Program:
```

#Program to find the rank of a matrix.
#Developed by:VIJAYASHANKAR N 
#RegisterNumber:212225230301
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a = np.array([[1,2,3],[3,6,9]])
B = np.linalg.matrix_rank(a)
print(B)

```
## Output:
<img width="460" height="153" alt="brave_screenshot_lms2 ai saveetha in (1)" src="https://github.com/user-attachments/assets/7989d774-2cae-4aca-ac4a-3d5d8a474536" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

