# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: 
### Step 4: 

## Program:
    #Program to find the inverse of a matrix.
    #Developed by: Jude Clement Jose G
    #RegisterNumber:24005310
   
    import numpy as np
    A = np.array([[1, 0, 3],
                [-1, 2, -2],
                [2, 3, -1]])
    try:
        A_inv = np.linalg.inv(A)
        
        print(A_inv)
    except np.linalg.LinAlgError:
        print("The matrix is singular and cannot be inverted.")
## Output:
![alt text](image.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

