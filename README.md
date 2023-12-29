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
## 1-Norm of a Matrix
~~~python
'''
Program to find the 1-Norm of a matrix.
Developed by: NATARAJ KUMARAN S
RegisterNumber: 23003973
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix ="{:.2f}".format(ans)
print(norm_of_matrix)
~~~


## 2-Norm of a Matrix
~~~python
'''
Program to find 2-norm of a matrix.
Developed by: NATARAJ KUMARAN S
RegisterNumber: 23003973
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
~~~
## Infinity Norm of a Matrix
~~~python
'''
Program  to find the Infinity of a matrix.
Developed by: NATARAJ KUMARAN S
RegisterNumber: 23003973
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
~~~




## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-29 182612](https://github.com/nataraj26/Norm-of-a-matrix/assets/147514615/6aa5908f-1413-4dbc-8c10-b3c3c93d273f)

<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot 2023-12-29 182634](https://github.com/nataraj26/Norm-of-a-matrix/assets/147514615/7f317389-1572-491a-b61e-bc1839aef928)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot 2023-12-29 182649](https://github.com/nataraj26/Norm-of-a-matrix/assets/147514615/e3f2a2e7-73e4-493a-8c8a-8f4f60933d64)


<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
