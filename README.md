# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)
```
## Output:
<img width="1030" height="765" alt="image" src="https://github.com/user-attachments/assets/a2f7e3ef-b462-428c-ad13-f0c78b6cc5cf" />

<img width="1097" height="292" alt="image" src="https://github.com/user-attachments/assets/42f31fe5-c653-44d8-b625-260896a01bdf" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

