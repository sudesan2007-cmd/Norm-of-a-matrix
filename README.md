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
### 1-Norm of a Matrix
<br><img width="1919" height="905" alt="Screenshot 2025-11-27 102534" src="https://github.com/user-attachments/assets/93424776-c553-4352-ad39-5aa7f08f484e" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="1919" height="867" alt="Screenshot 2025-11-27 102606" src="https://github.com/user-attachments/assets/f7cc86fb-3d30-4dc5-8b12-9a7f541976b1" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1919" height="845" alt="Screenshot 2025-11-27 102625" src="https://github.com/user-attachments/assets/d8eb923c-4429-47aa-8b00-1518ab22a221" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
