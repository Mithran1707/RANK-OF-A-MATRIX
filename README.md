# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
###Step 1: First import numpy module with nickname as np
###Step 2: Then give the matrix row in np.array()
###Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix and store it in the variable (i.e; rank)
###Step 4: Now print the rank to get the output
## Program:
import numpy as np
A = np.array([[1, 2, 3],
              [3, 6, 9]])
rank = np.linalg.matrix_rank(A)
print(rank)
## Output:
<img width="513" height="129" alt="Screenshot 2026-02-14 141606" src="https://github.com/user-attachments/assets/97af2b3c-d198-4dc6-b055-7a75efb1fbaf" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

