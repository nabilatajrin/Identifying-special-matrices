# Identifying-special-matrices
This assignment contains a function that will test if a 4×4 matrix is singular, i.e. to determine if an inverse exists, before calculating it.
The method of converting a matrix is used to echelon form, and testing if this fails by leaving zeros that can’t be removed on the leading diagonal.

#### Matrices in Python
In the numpy package in Python, matrices are indexed using zero for the top-most column and left-most row. I.e., the matrix structure looks like this:

A[0, 0]  A[0, 1]  A[0, 2]  A[0, 3] <br>
A[1, 0]  A[1, 1]  A[1, 2]  A[1, 3] <br>
A[2, 0]  A[2, 1]  A[2, 2]  A[2, 3] <br>
A[3, 0]  A[3, 1]  A[3, 2]  A[3, 3] <br>

We can access the value of each element individually using, <br>
A[n, m] <br>

which will give the n'th row and m'th column (starting with zero). We can also access a whole row at a time using, <br>
A[n] <br>

Which we will see will be useful when calculating linear combinations of rows.
