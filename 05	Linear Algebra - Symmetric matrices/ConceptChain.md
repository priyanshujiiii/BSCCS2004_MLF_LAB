1) complex matrix
   # Inner product & length ||x||^2 = x^T * x
   # Length of complex vector ||x|| = x-^T * x
   # checking these function x*y = (x*y)--
       x*cy = c*xy
       cx*y = c-*xy
   # conjugate of transpose A^*
   #   CHECK A** = A
        (AB)* = A*B*
        Real case value 
        A^T^T = A
        (AB)^T=A^T*B^T
   # Inner Product = x.y = x*y
 
 2) Hermintian Matrix
    If matrix A* = A then it is a Hermintian Matrix.
    
   # Properties of hermintian matrix
        1) Diagonal values of Hermintian matrix is always real.
        2) If a is hermintian matrix then the distinct eigen values are orthogonal.
   
   # Remarks
        1) The equivalent of hermintian matrix in the "real" case its "real symmetric matrix"
           all real symmetric matrix are hermintian.
        2) If no eigen values is repeated (=we havent distinct eigen values for n*n matrix A),then
            A is digonziable 
        3) if x and y are orthogonal then{x,y} it is linearly independent set 

3) Unitary Matrix
        A matrix is said to be unitary matrix   if it is square and has orthonomal columns
        Real case Q^T * Q = I
        COMPLEX CASE: U* * U = I, U^-1 = U*
        
        
        # PROPERTIES OF UNITARY MATRIX 
        1) Length remain unchanged ||Ux|| = ||U||
        2) Eigenvalues of a unitary matrix U have absolute value 
        3) if λ is an value of U,then |λ| = 1 
        4) Eigenvector corresponding to different eigenvalues of unitary matrix U are orthogonal
        5) For a Hermintian matrix A, we can find a unitary matrix U s.t
            A = U λ U* ,λ is a diagonal matrix with eigen values pf A.
        6) Real case: For a real symmetric matrix A, we can find a orthogonal matrix Q = (Q^T * Q = I)
           such that A= Q λ Q^T
        
