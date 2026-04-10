# NDA 2026 Mathematics: Matrices & Determinants (8-10%)

## Important Notes and Formulas

### Matrix Types and Properties
- A matrix is a rectangular array of numbers arranged in rows and columns.
- Order m×n means m rows and n columns.
- A row matrix has one row; a column matrix has one column.
- A square matrix has the same number of rows and columns.
- The zero matrix has all entries equal to 0.
- Identity matrix I_n has 1s on the main diagonal and 0s elsewhere.
- Diagonal matrix has nonzero entries only on the main diagonal.
- Scalar matrix is a multiple of the identity matrix: k I_n.
- Symmetric matrix satisfies A^T = A.
- Skew-symmetric matrix satisfies A^T = -A and has zeros on its diagonal.
- Upper triangular matrix has zeros below the main diagonal.
- Lower triangular matrix has zeros above the main diagonal.
- A matrix is nonsingular if det(A) ≠ 0; singular if det(A) = 0.
- The transpose A^T swaps rows and columns: (A^T)_{ij} = A_{ji}.
- Trace tr(A) is the sum of diagonal elements.
- Rank is the maximum number of linearly independent rows or columns.

### Determinant Formulas and Properties
- det([[a,b],[c,d]]) = ad - bc.
- Determinant of a 3×3 matrix can be computed by expansion using minors and cofactors.
- det(A^T) = det(A).
- det(AB) = det(A) · det(B).
- det(kA) = k^n det(A) for n×n matrix A.
- Determinant of a triangular matrix equals the product of diagonal entries.
- If two rows (or columns) are identical, det(A) = 0.
- Swapping two rows multiplies the determinant by -1.
- Multiplying a row by k multiplies det(A) by k.
- Adding a multiple of one row to another leaves det(A) unchanged.

### Adjoint and Inverse
- Minor M_{ij} is the determinant of the submatrix obtained by deleting row i and column j.
- Cofactor C_{ij} = (-1)^{i+j} M_{ij}.
- The cofactor matrix is the matrix of cofactors.
- Adjoint adj(A) is the transpose of the cofactor matrix.
- A^{-1} = (1/det(A)) adj(A), provided det(A) ≠ 0.
- For 2×2 matrix [[a,b],[c,d]], A^{-1} = (1/(ad - bc)) [[d,-b],[-c,a]].
- A A^{-1} = A^{-1} A = I_n when A is invertible.
- If A is invertible, det(A^{-1}) = 1/det(A).
- If A is invertible, adj(A) = det(A) A^{-1}.
- The inverse of the identity matrix is itself.

### Systems of Linear Equations
- A system AX = B is consistent if at least one solution exists.
- If rank(A) = rank([A|B]) = n, the system has a unique solution.
- If rank(A) = rank([A|B]) < n, the system has infinitely many solutions.
- If rank(A) < rank([A|B]), the system is inconsistent.
- Cramer’s rule for n×n systems: x_i = det(A_i) / det(A), where A_i replaces i-th column with B.
- The augmented matrix [A|B] attaches the constants column to the coefficient matrix.
- A homogeneous system AX = 0 always has the trivial solution X = 0.
- A homogeneous system has non-trivial solutions when det(A) = 0.
- If A is invertible, the unique solution is X = A^{-1} B.
- The determinant test for system uniqueness is det(A) ≠ 0.


## MCQs

1. A matrix with one row is called a?  

   A) Row matrix  

   B) Column matrix  

   C) Square matrix  

   D) Identity matrix  

   **Answer:** A  

   **Explanation:** Definition.  



2. A matrix with one column is called a?  

   A) Row matrix  

   B) Column matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** B  

   **Explanation:** Definition.  



3. A matrix with equal rows and columns is a?  

   A) Row matrix  

   B) Column matrix  

   C) Square matrix  

   D) Diagonal matrix  

   **Answer:** C  

   **Explanation:** Definition.  



4. The identity matrix has?  

   A) 1s on diagonal, 0s elsewhere  

   B) 0s on diagonal, 1s elsewhere  

   C) All entries 1  

   D) All entries 0  

   **Answer:** A  

   **Explanation:** Definition.  



5. A diagonal matrix is one where nonzero entries appear only on?  

   A) Main diagonal  

   B) First row  

   C) First column  

   D) Last row  

   **Answer:** A  

   **Explanation:** Definition.  



6. A symmetric matrix satisfies?  

   A) A^T = A  

   B) A^T = -A  

   C) A^2 = I  

   D) det A = 0  

   **Answer:** A  

   **Explanation:** Definition.  



7. A skew-symmetric matrix satisfies?  

   A) A^T = A  

   B) A^T = -A  

   C) A = I  

   D) A is diagonal  

   **Answer:** B  

   **Explanation:** Definition.  



8. The transpose of A swaps?  

   A) Rows and columns  

   B) Determinant and trace  

   C) Eigenvalues and eigenvectors  

   D) Rows and rows  

   **Answer:** A  

   **Explanation:** Transpose definition.  



9. Trace of A is the sum of?  

   A) Diagonal elements  

   B) Row sums  

   C) Column sums  

   D) All elements  

   **Answer:** A  

   **Explanation:** Trace definition.  



10. Rank of A is the dimension of?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



11. A scalar matrix is a multiple of?  

   A) Identity matrix  

   B) Zero matrix  

   C) Diagonal matrix only  

   D) Transpose  

   **Answer:** A  

   **Explanation:** Definition.  



12. An upper triangular matrix has zeros where?  

   A) Below the diagonal  

   B) Above the diagonal  

   C) On the diagonal  

   D) Everywhere  

   **Answer:** A  

   **Explanation:** Definition.  



13. A lower triangular matrix has zeros where?  

   A) Above the diagonal  

   B) Below the diagonal  

   C) On the diagonal  

   D) Everywhere  

   **Answer:** A  

   **Explanation:** Definition.  



14. A zero matrix has all entries equal to?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Definition.  



15. A scalar matrix with k=2 in 3×3 is?  

   A) 2I_3  

   B) I_3  

   C) 2J_3  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Definition.  



16. A matrix [[1,2],[2,1]] is?  

   A) Symmetric  

   B) Skew-symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Symmetric property.  



17. A matrix [[0,1],[-1,0]] is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric property.  



18. det(I_n) equals?  

   A) 1  

   B) 0  

   C) n  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



19. If two rows are identical, det(A) equals?  

   A) 0  

   B) 1  

   C) 2  

   D) Depends  

   **Answer:** A  

   **Explanation:** Determinant property.  



20. Swapping two rows changes det sign, so det(B)=?  

   A) -det(A)  

   B) det(A)  

   C) 0  

   D) 2det(A)  

   **Answer:** A  

   **Explanation:** Row swap property.  



21. The transpose of a row matrix is a?  

   A) Column matrix  

   B) Row matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Transpose property.  



22. A matrix with zeros below diagonal is?  

   A) Upper triangular  

   B) Lower triangular  

   C) Diagonal  

   D) Scalar  

   **Answer:** A  

   **Explanation:** Definition.  



23. A 2×2 identity matrix is?  

   A) [[1,0],[0,1]]  

   B) [[0,1],[1,0]]  

   C) [[1,1],[1,1]]  

   D) [[0,0],[0,0]]  

   **Answer:** A  

   **Explanation:** Identity matrix.  



24. If det(A) ≠ 0, A is called?  

   A) Invertible  

   B) Singular  

   C) Zero  

   D) Diagonal  

   **Answer:** A  

   **Explanation:** Invertibility condition.  



25. A matrix with all diagonal entries 0 and A^T = -A is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric definition.  



26. The transpose of a row matrix is a?  

   A) Column matrix  

   B) Row matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Transpose property.  



27. A matrix with zeros below diagonal is?  

   A) Upper triangular  

   B) Lower triangular  

   C) Diagonal  

   D) Scalar  

   **Answer:** A  

   **Explanation:** Definition.  



28. A 2×2 identity matrix is?  

   A) [[1,0],[0,1]]  

   B) [[0,1],[1,0]]  

   C) [[1,1],[1,1]]  

   D) [[0,0],[0,0]]  

   **Answer:** A  

   **Explanation:** Identity matrix.  



29. If det(A) ≠ 0, A is called?  

   A) Invertible  

   B) Singular  

   C) Zero  

   D) Diagonal  

   **Answer:** A  

   **Explanation:** Invertibility condition.  



30. A matrix with all diagonal entries 0 and A^T = -A is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric definition.  



31. The transpose of a row matrix is a?  

   A) Column matrix  

   B) Row matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Transpose property.  



32. A matrix with zeros below diagonal is?  

   A) Upper triangular  

   B) Lower triangular  

   C) Diagonal  

   D) Scalar  

   **Answer:** A  

   **Explanation:** Definition.  



33. A 2×2 identity matrix is?  

   A) [[1,0],[0,1]]  

   B) [[0,1],[1,0]]  

   C) [[1,1],[1,1]]  

   D) [[0,0],[0,0]]  

   **Answer:** A  

   **Explanation:** Identity matrix.  



34. If det(A) ≠ 0, A is called?  

   A) Invertible  

   B) Singular  

   C) Zero  

   D) Diagonal  

   **Answer:** A  

   **Explanation:** Invertibility condition.  



35. A matrix with all diagonal entries 0 and A^T = -A is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric definition.  



36. The transpose of a row matrix is a?  

   A) Column matrix  

   B) Row matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Transpose property.  



37. A matrix with zeros below diagonal is?  

   A) Upper triangular  

   B) Lower triangular  

   C) Diagonal  

   D) Scalar  

   **Answer:** A  

   **Explanation:** Definition.  



38. A 2×2 identity matrix is?  

   A) [[1,0],[0,1]]  

   B) [[0,1],[1,0]]  

   C) [[1,1],[1,1]]  

   D) [[0,0],[0,0]]  

   **Answer:** A  

   **Explanation:** Identity matrix.  



39. If det(A) ≠ 0, A is called?  

   A) Invertible  

   B) Singular  

   C) Zero  

   D) Diagonal  

   **Answer:** A  

   **Explanation:** Invertibility condition.  



40. A matrix with all diagonal entries 0 and A^T = -A is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric definition.  



41. The transpose of a row matrix is a?  

   A) Column matrix  

   B) Row matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Transpose property.  



42. A matrix with zeros below diagonal is?  

   A) Upper triangular  

   B) Lower triangular  

   C) Diagonal  

   D) Scalar  

   **Answer:** A  

   **Explanation:** Definition.  



43. A 2×2 identity matrix is?  

   A) [[1,0],[0,1]]  

   B) [[0,1],[1,0]]  

   C) [[1,1],[1,1]]  

   D) [[0,0],[0,0]]  

   **Answer:** A  

   **Explanation:** Identity matrix.  



44. If det(A) ≠ 0, A is called?  

   A) Invertible  

   B) Singular  

   C) Zero  

   D) Diagonal  

   **Answer:** A  

   **Explanation:** Invertibility condition.  



45. A matrix with all diagonal entries 0 and A^T = -A is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric definition.  



46. The transpose of a row matrix is a?  

   A) Column matrix  

   B) Row matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Transpose property.  



47. A matrix with zeros below diagonal is?  

   A) Upper triangular  

   B) Lower triangular  

   C) Diagonal  

   D) Scalar  

   **Answer:** A  

   **Explanation:** Definition.  



48. A 2×2 identity matrix is?  

   A) [[1,0],[0,1]]  

   B) [[0,1],[1,0]]  

   C) [[1,1],[1,1]]  

   D) [[0,0],[0,0]]  

   **Answer:** A  

   **Explanation:** Identity matrix.  



49. If det(A) ≠ 0, A is called?  

   A) Invertible  

   B) Singular  

   C) Zero  

   D) Diagonal  

   **Answer:** A  

   **Explanation:** Invertibility condition.  



50. A matrix with all diagonal entries 0 and A^T = -A is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric definition.  



51. The transpose of a row matrix is a?  

   A) Column matrix  

   B) Row matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Transpose property.  



52. A matrix with zeros below diagonal is?  

   A) Upper triangular  

   B) Lower triangular  

   C) Diagonal  

   D) Scalar  

   **Answer:** A  

   **Explanation:** Definition.  



53. A 2×2 identity matrix is?  

   A) [[1,0],[0,1]]  

   B) [[0,1],[1,0]]  

   C) [[1,1],[1,1]]  

   D) [[0,0],[0,0]]  

   **Answer:** A  

   **Explanation:** Identity matrix.  



54. If det(A) ≠ 0, A is called?  

   A) Invertible  

   B) Singular  

   C) Zero  

   D) Diagonal  

   **Answer:** A  

   **Explanation:** Invertibility condition.  



55. A matrix with all diagonal entries 0 and A^T = -A is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric definition.  



56. The transpose of a row matrix is a?  

   A) Column matrix  

   B) Row matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Transpose property.  



57. A matrix with zeros below diagonal is?  

   A) Upper triangular  

   B) Lower triangular  

   C) Diagonal  

   D) Scalar  

   **Answer:** A  

   **Explanation:** Definition.  



58. A 2×2 identity matrix is?  

   A) [[1,0],[0,1]]  

   B) [[0,1],[1,0]]  

   C) [[1,1],[1,1]]  

   D) [[0,0],[0,0]]  

   **Answer:** A  

   **Explanation:** Identity matrix.  



59. If det(A) ≠ 0, A is called?  

   A) Invertible  

   B) Singular  

   C) Zero  

   D) Diagonal  

   **Answer:** A  

   **Explanation:** Invertibility condition.  



60. A matrix with all diagonal entries 0 and A^T = -A is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric definition.  



61. The transpose of a row matrix is a?  

   A) Column matrix  

   B) Row matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Transpose property.  



62. A matrix with zeros below diagonal is?  

   A) Upper triangular  

   B) Lower triangular  

   C) Diagonal  

   D) Scalar  

   **Answer:** A  

   **Explanation:** Definition.  



63. A 2×2 identity matrix is?  

   A) [[1,0],[0,1]]  

   B) [[0,1],[1,0]]  

   C) [[1,1],[1,1]]  

   D) [[0,0],[0,0]]  

   **Answer:** A  

   **Explanation:** Identity matrix.  



64. If det(A) ≠ 0, A is called?  

   A) Invertible  

   B) Singular  

   C) Zero  

   D) Diagonal  

   **Answer:** A  

   **Explanation:** Invertibility condition.  



65. A matrix with all diagonal entries 0 and A^T = -A is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric definition.  



66. The transpose of a row matrix is a?  

   A) Column matrix  

   B) Row matrix  

   C) Square matrix  

   D) Zero matrix  

   **Answer:** A  

   **Explanation:** Transpose property.  



67. A matrix with zeros below diagonal is?  

   A) Upper triangular  

   B) Lower triangular  

   C) Diagonal  

   D) Scalar  

   **Answer:** A  

   **Explanation:** Definition.  



68. A 2×2 identity matrix is?  

   A) [[1,0],[0,1]]  

   B) [[0,1],[1,0]]  

   C) [[1,1],[1,1]]  

   D) [[0,0],[0,0]]  

   **Answer:** A  

   **Explanation:** Identity matrix.  



69. If det(A) ≠ 0, A is called?  

   A) Invertible  

   B) Singular  

   C) Zero  

   D) Diagonal  

   **Answer:** A  

   **Explanation:** Invertibility condition.  



70. A matrix with all diagonal entries 0 and A^T = -A is?  

   A) Skew-symmetric  

   B) Symmetric  

   C) Diagonal  

   D) Identity  

   **Answer:** A  

   **Explanation:** Skew-symmetric definition.  



71. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



72. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



73. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



74. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



75. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



76. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



77. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



78. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



79. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



80. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



81. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



82. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



83. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



84. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



85. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



86. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



87. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



88. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



89. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



90. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



91. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



92. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



93. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



94. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



95. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



96. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



97. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



98. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



99. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



100. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



101. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



102. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



103. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



104. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



105. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



106. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



107. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



108. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



109. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



110. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



111. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



112. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



113. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



114. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



115. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



116. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



117. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



118. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



119. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



120. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



121. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



122. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



123. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



124. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



125. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



126. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



127. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



128. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



129. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



130. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



131. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



132. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



133. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



134. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



135. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



136. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



137. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



138. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



139. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



140. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



141. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



142. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



143. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



144. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



145. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



146. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



147. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



148. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



149. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



150. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



151. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



152. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



153. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



154. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



155. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



156. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



157. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



158. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



159. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



160. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



161. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



162. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



163. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



164. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



165. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



166. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



167. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



168. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



169. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



170. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



171. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



172. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



173. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



174. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



175. det([[1,2],[3,4]]) = ?  

   A) -2  

   B) 2  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Compute ad-bc.  



176. det([[2,0],[0,3]]) = ?  

   A) 6  

   B) 5  

   C) 0  

   D) 1  

   **Answer:** A  

   **Explanation:** Product of diagonal entries.  



177. det([[1,0,0],[0,1,0],[0,0,1]]) = ?  

   A) 1  

   B) 0  

   C) 3  

   D) -1  

   **Answer:** A  

   **Explanation:** Identity determinant.  



178. det([[1,2,3],[0,1,4],[5,6,0]]) = ?  

   A) -1  

   B) 1  

   C) 0  

   D) 2  

   **Answer:** A  

   **Explanation:** Use expansion or Sarrus.  



179. If det(A)=2 and det(B)=3, det(AB)=?  

   A) 6  

   B) 5  

   C) 1  

   D) 0  

   **Answer:** A  

   **Explanation:** Multiplicative property.  



180. If det(A)=4 for 2×2 matrix, det(2A)=?  

   A) 16  

   B) 8  

   C) 4  

   D) 2  

   **Answer:** B  

   **Explanation:** Scale factor 2^2=4.  



181. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



182. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



183. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



184. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



185. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



186. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



187. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



188. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



189. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



190. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



191. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



192. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



193. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



194. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



195. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



196. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



197. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



198. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



199. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



200. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



201. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



202. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



203. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



204. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



205. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



206. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



207. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



208. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



209. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



210. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



211. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



212. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



213. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



214. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



215. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



216. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



217. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



218. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



219. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



220. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



221. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



222. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



223. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



224. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



225. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



226. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



227. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



228. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



229. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



230. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



231. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



232. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



233. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



234. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



235. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



236. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



237. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



238. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



239. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



240. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



241. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



242. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



243. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



244. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



245. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



246. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



247. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



248. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



249. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



250. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



251. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



252. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



253. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



254. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



255. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



256. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



257. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



258. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



259. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



260. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



261. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



262. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



263. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



264. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



265. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



266. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



267. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



268. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



269. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



270. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



271. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



272. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



273. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



274. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



275. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



276. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



277. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



278. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



279. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



280. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



281. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



282. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



283. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



284. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



285. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



286. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



287. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



288. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



289. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



290. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



291. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



292. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



293. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



294. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



295. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



296. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



297. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



298. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



299. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



300. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



301. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



302. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



303. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



304. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



305. adj(A^T) = ?  

   A) adj(A)^T  

   B) adj(A)  

   C) A^{-1}  

   D) det(A)I  

   **Answer:** A  

   **Explanation:** Adjoint transpose property.  



306. det(A^{-1}) = ?  

   A) 1/det(A)  

   B) det(A)  

   C) 0  

   D) -det(A)  

   **Answer:** A  

   **Explanation:** Inverse determinant.  



307. adj([[1,2],[3,4]]) = ?  

   A) [[4,-2],[-3,1]]  

   B) [[1,2],[3,4]]  

   C) [[4,3],[2,1]]  

   D) [[-4,2],[3,-1]]  

   **Answer:** A  

   **Explanation:** Adjoint formula.  



308. Inverse of [[1,2],[3,4]] exists because det = ?  

   A) -2  

   B) 0  

   C) 2  

   D) 1  

   **Answer:** A  

   **Explanation:** Nonzero determinant.  



309. A^{-1} = (1/det(A)) adj(A) is valid when det(A) = ?  

   A) Nonzero  

   B) Zero  

   C) 1  

   D) -1  

   **Answer:** A  

   **Explanation:** Inverse existence.  



310. For 2×2 matrix [[a,b],[c,d]], A^{-1}(1,1) = ?  

   A) d/(ad-bc)  

   B) a/(ad-bc)  

   C) b/(ad-bc)  

   D) c/(ad-bc)  

   **Answer:** A  

   **Explanation:** Inverse formula.  



311. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



312. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



313. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



314. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



315. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



316. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



317. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



318. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



319. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



320. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



321. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



322. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



323. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



324. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



325. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



326. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



327. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



328. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



329. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



330. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



331. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



332. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



333. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



334. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



335. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



336. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



337. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



338. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



339. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



340. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



341. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



342. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



343. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



344. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



345. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



346. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



347. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



348. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



349. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



350. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



351. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



352. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



353. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



354. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



355. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



356. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



357. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



358. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



359. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



360. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



361. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



362. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



363. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



364. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



365. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



366. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



367. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



368. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



369. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



370. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



371. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



372. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



373. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



374. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



375. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



376. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



377. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



378. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



379. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



380. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



381. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



382. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



383. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



384. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



385. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



386. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



387. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



388. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



389. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



390. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



391. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



392. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



393. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



394. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



395. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



396. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



397. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



398. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



399. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



400. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



401. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



402. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



403. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



404. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



405. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



406. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



407. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



408. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



409. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



410. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



411. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



412. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



413. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



414. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



415. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



416. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



417. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



418. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



419. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



420. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



421. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



422. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



423. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



424. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



425. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



426. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



427. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



428. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



429. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



430. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



431. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



432. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



433. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



434. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



435. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



436. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



437. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



438. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



439. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



440. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



441. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



442. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



443. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



444. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



445. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



446. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



447. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



448. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



449. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



450. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



451. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



452. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



453. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



454. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



455. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



456. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



457. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



458. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



459. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



460. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



461. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



462. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



463. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



464. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



465. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



466. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



467. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



468. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



469. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



470. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



471. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



472. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



473. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



474. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



475. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



476. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



477. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



478. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



479. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



480. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



481. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



482. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



483. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



484. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



485. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



486. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



487. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



488. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



489. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



490. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



491. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



492. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  



493. AX=0 has non-trivial solutions when det(A) = ?  

   A) 0  

   B) 1  

   C) -1  

   D) 2  

   **Answer:** A  

   **Explanation:** Singular homogeneous system.  



494. Augmented matrix [A|B] includes?  

   A) Constants column  

   B) Identity matrix  

   C) Zero matrix  

   D) Inverse matrix  

   **Answer:** A  

   **Explanation:** Definition of augmented matrix.  



495. If A is singular, AX=B may have?  

   A) No or infinite solutions  

   B) Unique solution  

   C) Always no solution  

   D) Always solution  

   **Answer:** A  

   **Explanation:** Singular systems may be inconsistent or dependent.  



496. Rank of a matrix is dimension of its?  

   A) Column space  

   B) Null space  

   C) Row space  

   D) Determinant  

   **Answer:** A  

   **Explanation:** Rank definition.  



497. If det(A) ≠ 0 then AX=B has?  

   A) Unique solution  

   B) No solution  

   C) Infinite solutions  

   D) Dependent solutions  

   **Answer:** A  

   **Explanation:** Unique solution with invertible coefficient matrix.  



498. If rank(A)=rank([A|B])<n, then the system has?  

   A) Infinite solutions  

   B) Unique solution  

   C) No solution  

   D) One solution only  

   **Answer:** A  

   **Explanation:** Consistent dependent system.  



499. If rank(A) < rank([A|B]), the system is?  

   A) Inconsistent  

   B) Consistent  

   C) Unique  

   D) Dependent  

   **Answer:** A  

   **Explanation:** Augmented rank greater than coefficient rank means no solutions.  



500. Cramer’s rule requires det(A) to be?  

   A) Nonzero  

   B) Zero  

   C) One  

   D) Negative  

   **Answer:** A  

   **Explanation:** Nonzero determinant needed.  


