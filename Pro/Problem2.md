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

The element at position **C(i, j)** in the resulting matrix is calculated using the **dot product** of the _i-th row_ of Matrix **A** and the _j-th column_ of Matrix **B**.

**C[i][j] = Σ (A[i][k] × B[k][j])**  
Where the summation is from **k = 0** to **M-1**.

- **A[i][k]** represents the elements from the i-th row of Matrix A.
- **B[k][j]** represents the elements from the j-th column of Matrix B.
- **C[i][j]** is the sum of all these multiplications.

---

## 🧑‍🏫 **Example**

Matrix A:

```
1 2
3 4
```

Matrix B:

```
5 6
7 8
```

### Calculate **C[0][0]**:

```
C[0][0] = (1 × 5) + (2 × 7) = 5 + 14 = 19
```

### Calculate **C[0][1]**:

```
C[0][1] = (1 × 6) + (2 × 8) = 6 + 16 = 22
```

### Calculate **C[1][0]**:

```
C[1][0] = (3 × 5) + (4 × 7) = 15 + 28 = 43
```

### Calculate **C[1][1]**:

```
C[1][1] = (3 × 6) + (4 × 8) = 18 + 32 = 50
```

---

## ✅ **Final Result**

Matrix C:

```
19 22
43 50
```