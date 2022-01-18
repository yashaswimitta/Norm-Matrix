# 2-Norm of a matrix
## Aim
To write a program to find the 2-norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()
2. The 2-Norm of a matrix is given by ![input.jpg](normeqn1.jpg) 
3. Find the 2-norm of the matrix using np.linalg.norm()
4. Print the norm of the matrix in two decimal places.
## Program:
~~~
Program to find 2-norm of a matrix.
Developed by: yashaswimitta
RegisterNumber:21002549
# Type your code here
import numpy as np
n=np.array(eval(input()))
ans=np.linalg.norm(n,2)
b="{:.2f}".format(ans)
print(b)
~~~
## Sample Input and Output:
![GitHub Logo](2norm.png.png)


## Result
Thus the program for 2-norm of a matrix is written and verified.
