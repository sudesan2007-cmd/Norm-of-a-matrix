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
# Register No:SUDESAN T
# Developed By:25018208
# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))

norm=np.linalg.norm(A,1)
print(norm)

# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(f"{norm:.2f}")


# Infinity Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,np.inf)
print(norm)
```
## Output:
<img width="1313" height="793" alt="Screenshot 2025-11-27 101753" src="https://github.com/user-attachments/assets/9efae332-9321-434c-bf8d-8470a4758cae" />
<img width="889" height="766" alt="Screenshot 2025-11-27 101807" src="https://github.com/user-attachments/assets/5fc16dfc-35a8-4f5e-9a72-9ff30097c6dc" />
<img width="1171" height="747" alt="Screenshot 2025-11-27 101821" src="https://github.com/user-attachments/assets/ff7c6d21-fe4f-47c0-bef5-242d95ba3381" />


### 1-Norm of a Matrix
<br>
<br>
<br>

### 2-Norm of a Matrix
<br>
<br>
<br>

### Infinity Norm of a Matrix
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
