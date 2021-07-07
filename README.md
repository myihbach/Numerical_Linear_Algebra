## Numerical Linear Algebra

This repository contains the following algorithms:
- `GMRES` : Generalized Minimal Residual Method, an iterative method to approximate the solution of AX = b by the vector in a Krylov subspace with minimal residual. The `Arnoldi` iteration is used to find this vector. 
- `Symmetric Lnaczos` : is a direct algorithm to find the m **most important** eigenvalues and eigenvectors of an n × n Hermitian matrix, where m is often but not necessarily much smaller than n.
- `NonSymmetric Lnaczos` : in case of Non symmetric (Non hermitian) matrices
- `BiCG` : Biconjugate Gradient Method, is an algorithm to solve systems of linear equations Ax = b, and does not require the matrix A  to be self-adjoint (Hermitian), but instead one needs to perform multiplications by the conjugate transpose A*.
- `BICGSTAB` : Biconjugate Gradient Stabilized Method, can be viewed as a combination of `BiCG` and `GMRES` where each `BiCG` step is followed by a `GMRES`.
- `Golub_Kuhan Bidiagobalisation` : suggest a particular method for producing a bidiagonal matrix with the same singular values as A. This method is related to the
Lanczos method of minimized iterations for tridiagonalizing a symmetric matrix, and like that method is ideally suited for `large sparse matrices`.

## More algorithms will be added in the future 😇
