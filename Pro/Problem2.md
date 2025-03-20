## Pro: Matrix Multiplication
### Problem:
Write a program to multiply two matrices of size NxM and MxP.

Example:

naa tay 1st matrix
Matrix A = [[1, 2],
            [3, 4]]

ug second matrix
Matrix B = [[5, 6],
            [7, 8]]

Output: [[19, 22],
         [43, 50]]  

# 📗 How to Calculate Each Element

The element at position **C(i, j)** in the resulting matrix is calculated using the **dot product** of the *i-th row* of Matrix **A** and the *j-th column* of Matrix **B**.

\[
C[i][j] = \sum_{k=0}^{M-1} (A[i][k] \times B[k][j])
\]

- \( A[i][k] \) represents the elements from the i-th row of Matrix A.  
- \( B[k][j] \) represents the elements from the j-th column of Matrix B.  
- \( C[i][j] \) is the sum of all these multiplications.  

---

## 🧑‍🏫 **Example**  

\[
A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}, \quad B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix}
\]

### Calculate \( C[0][0] \):

\[
C[0][0] = (1 \times 5) + (2 \times 7) = 5 + 14 = 19
\]

### Calculate \( C[0][1] \):

\[
C[0][1] = (1 \times 6) + (2 \times 8) = 6 + 16 = 22
\]

### Calculate \( C[1][0] \):

\[
C[1][0] = (3 \times 5) + (4 \times 7) = 15 + 28 = 43
\]

### Calculate \( C[1][1] \):

\[
C[1][1] = (3 \times 6) + (4 \times 8) = 18 + 32 = 50
\]

---

## ✅ **Final Result**  

\[
C = \begin{bmatrix} 19 & 22 \\ 43 & 50 \end{bmatrix}
\]
