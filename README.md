# Singular Value Decomposition (SVD) using NumPy

This project demonstrates the manual implementation of **Singular Value Decomposition (SVD)** using NumPy.

The goal of this project is to understand the mathematical foundation of SVD by computing:

- \( A^T A \)
- Eigenvalues and Eigenvectors
- Singular values
- Matrices \( U \), \( \Sigma \), and \( V^T \)
- Verification of the decomposition \( A = U \Sigma V^T \)
- 
## Matrix Used

\[
A =
\begin{bmatrix}
-1 & -7 \\
-1 & -7
\end{bmatrix}
\]

This matrix has rank 1, which makes it a good example for understanding:

- Non-zero singular values
- Rank deficiency
- Subspace representation

## Mathematical Background

For a matrix \( A \in \mathbb{R}^{m \times n} \), the Singular Value Decomposition is:

\[
A = U \Sigma V^T
\]

Where:

- **U** → Orthogonal matrix (left singular vectors)
- **Σ** → Diagonal matrix (singular values)
- **Vᵀ** → Transpose of orthogonal matrix (right singular vectors)

Singular values are computed as:

\[
\sigma_i = \sqrt{\lambda_i}
\]

Where \( \lambda_i \) are the eigenvalues of \( A^T A \).

## Features

- Manual computation of SVD steps
- Eigenvalue and eigenvector calculation
- Singular value computation
- Reconstruction check
- Error verification

## Requirements

- Python 3.x
- NumPy

Install NumPy using:

```bash
pip install numpy
