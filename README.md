# matrix-solving
-You can evaluate the solution vector (x for Ax=b) where A is n*n matrix and 
where b is n*1 vector trough this program.

-The source file of this program and matrix and vector files should be in the
same folder for this program to reach files.

-Matrix and vector file should be in txt format.

-You will be asked the name of matrix file (A for Ax=b) and vector file
(b for Ax=b). Inputs should be like "name_of_the_file.txt". 

-If you write the input (file name) incorrect, the program will not work and 
you will get warning like "unable to open file". 

-If matrix is singular, you will get warning like "matrix is singular".

-If your matrix is 2*2, you will see condition numbers of your matrix
at 1 and infinity.

-You will see your solutions on the screen if your matrix is nonsingular,
also file called "x.txt" will be generated in the folder in which the
solutions are written.

//Condition number case

e.g. when A= 1.000 1.000 and b= 2.000
	     1.000 1.001        2.000
	     
the solution through Gaussian elimination with partial pivoting is
x= [2 0]
when b= 2.000
        2.001
x= [1 1].

We see that very small change in "b vector" caused very large change
in the solution, that is why we can say that matrix is nearly singular.
Also since the condition number of this matrix at 1 and infinity is 4004,
which is very large we can say that this matrix is nearly singular.


