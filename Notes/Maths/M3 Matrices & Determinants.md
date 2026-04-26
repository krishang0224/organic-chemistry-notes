# M3 Matrices & Determinants

> [!tip] One Line
> Matrix = array of numbers with defined operations. Determinant = scalar from square matrix. Cramer's rule and inverse solve linear systems.

---

## Matrix Basics

**Order:** m × n (m rows, n columns)

### Types of Matrices
| Type | Description |
|------|-------------|
| Row matrix | 1 × n |
| Column matrix | m × 1 |
| Square matrix | m = n |
| Diagonal matrix | All off-diagonal elements = 0 |
| Identity matrix (I) | Diagonal = 1, rest = 0 |
| Zero matrix (O) | All elements = 0 |
| Symmetric | Aᵀ = A |
| Skew-symmetric | Aᵀ = –A (diagonal = 0) |

### Transpose (Aᵀ)
Rows ↔ Columns. (Aᵀ)ᵀ = A, (AB)ᵀ = BᵀAᵀ

---

## Matrix Operations

### Addition/Subtraction
Element-wise; only if same order.

### Scalar Multiplication
Each element multiplied by scalar.

### Matrix Multiplication
(m×n)(n×p) → (m×p); NOT commutative in general (AB ≠ BA).
```
(AB)ᵢⱼ = Σₖ aᵢₖ bₖⱼ
```

**Properties:**
- AI = IA = A (identity)
- A(BC) = (AB)C (associative)
- A(B+C) = AB + AC (distributive)

---

## Determinants

For 2×2: det[a b; c d] = ad – bc

For 3×3 (cofactor expansion along row 1):
```
|a b c|
|d e f| = a(ei–fh) – b(di–fg) + c(dh–eg)
|g h i|
```

### Properties of Determinants
1. |Aᵀ| = |A|
2. Swapping two rows/columns: sign changes
3. If two rows/columns identical: |A| = 0
4. Multiplying a row by k: |A| multiplies by k
5. |kA| = kⁿ|A| for n×n matrix
6. |AB| = |A||B|
7. If any row/column all zeros: |A| = 0
8. Row operations don't change |A| if we add multiples of other rows

### Minors & Cofactors
Minor Mᵢⱼ = determinant of submatrix obtained by deleting row i, col j.
Cofactor Cᵢⱼ = (–1)^(i+j) Mᵢⱼ

---

## Inverse of a Matrix

A matrix is invertible if |A| ≠ 0 (non-singular).

```
A⁻¹ = adj(A)/|A|
adj(A) = transpose of cofactor matrix
AA⁻¹ = A⁻¹A = I
```

**For 2×2:** If A = [a b; c d], A⁻¹ = (1/|A|)[d –b; –c a]

---

## System of Linear Equations

AX = B

**Cramer's Rule (for 2×2, 3×3):**
```
x = Dₓ/D,  y = D_y/D,  z = D_z/D
```
where D = |A|, Dₓ = |A with column x replaced by B|, etc.

**Using inverse:** X = A⁻¹B (when |A| ≠ 0)

**Consistency:**
- |A| ≠ 0: unique solution
- |A| = 0, (adj A)·B = 0: infinitely many solutions
- |A| = 0, (adj A)·B ≠ 0: no solution (inconsistent)

---

## Applications

**Area of triangle with vertices (x₁,y₁), (x₂,y₂), (x₃,y₃):**
```
Area = ½|x₁(y₂–y₃) + x₂(y₃–y₁) + x₃(y₁–y₂)|
     = ½|det[x₁ y₁ 1; x₂ y₂ 1; x₃ y₃ 1]|
```
Collinear if area = 0 → determinant = 0.

---

## Practice Questions
1. A = [1 2; 3 4]. Find |A| and A⁻¹.
2. Solve: 2x + y = 5, x – y = 1 using Cramer's rule.
3. For what value of k is the system x + y = 1, kx + y = 2 inconsistent?
4. If A is skew-symmetric of odd order, show |A| = 0.

> [!question]- Answers
> 1. |A| = 4–6 = –2; A⁻¹ = (1/–2)[4 –2; –3 1] = [–2 1; 3/2 –1/2]
> 2. D = |2 1; 1 –1| = –2–1 = –3; Dₓ = |5 1; 1 –1| = –6; D_y = |2 5; 1 1| = 2–5 = –3; x = –6/–3 = 2, y = –3/–3 = 1
> 3. D = |1 1; k 1| = 1–k = 0 → k=1; check if (adjA)·B ≠ 0 → inconsistent when k=1
> 4. Aᵀ = –A → |Aᵀ| = |–A| → |A| = (–1)ⁿ|A|; for odd n: |A| = –|A| → 2|A| = 0 → |A| = 0

---
**Previous: [[M2 Integration]]**
**Next: [[M4 Probability & Statistics]]**
