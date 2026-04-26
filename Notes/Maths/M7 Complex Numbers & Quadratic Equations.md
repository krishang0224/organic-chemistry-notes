# M7 Complex Numbers & Quadratic Equations

> [!tip] One Line
> i = √(–1). Complex: z = a+bi. Modulus-argument form: r(cosθ+i sinθ) = re^(iθ). Quadratic: roots from discriminant.

---

## Complex Numbers

### Basic Form
```
z = a + bi    (a = real part, b = imaginary part)
i² = –1, i³ = –i, i⁴ = 1    (cycle of period 4)
```

### Algebra of Complex Numbers
```
(a+bi) + (c+di) = (a+c) + (b+d)i
(a+bi)(c+di) = (ac–bd) + (ad+bc)i
```

**Conjugate:** z̄ = a – bi
- z·z̄ = a² + b² = |z|² (real number!)
- Division: multiply numerator and denominator by conjugate

### Modulus & Argument
```
|z| = √(a²+b²)    (modulus = distance from origin)
arg(z) = θ = tan⁻¹(b/a)    (argument = angle, –π < θ ≤ π)
```

### Polar/Euler Form
```
z = r(cosθ + i sinθ) = re^(iθ)
r = |z|, θ = arg(z)
```

**De Moivre's Theorem:**
```
(cosθ + i sinθ)ⁿ = cos(nθ) + i sin(nθ)
```
Used to find nth roots and powers of complex numbers.

### nth Roots of Unity
```
z = e^(2πik/n)    for k = 0, 1, ..., n–1
```
Sum of all nth roots of unity = 0.
Product of all nth roots = (–1)^(n+1).

**Cube roots of unity (ω):**
```
1, ω, ω²    where ω = e^(2πi/3) = –1/2 + i√3/2
ω³ = 1,   1 + ω + ω² = 0,   ω² = ω̄
```

---

## Argand Plane

Complex number z = a+bi plotted as point (a,b).
- |z₁ – z₂| = distance between z₁ and z₂
- |z| = r represents circle of radius r
- arg(z) = θ represents ray from origin

### Loci (Common ones)
- |z – a| = r: circle center a, radius r
- |z – a| = |z – b|: perpendicular bisector of segment ab
- arg(z – a) = θ: ray from a at angle θ

---

## Quadratic Equations

### Roots of ax² + bx + c = 0
```
x = (–b ± √D) / 2a    where D = b² – 4ac (discriminant)
```

| D | Nature of roots |
|----|----------------|
| D > 0 | Two distinct real roots |
| D = 0 | Two equal real roots |
| D < 0 | Two conjugate complex roots |

### Vieta's Formulas
If α, β are roots of ax² + bx + c = 0:
```
α + β = –b/a    (sum of roots)
αβ = c/a        (product of roots)
```

**Forming equation from roots:**
```
x² – (α+β)x + αβ = 0
```

### Nature of Roots for Real Coefficients
Complex roots always come in conjugate pairs: if α+iβ is root, so is α–iβ.

---

## Polynomial Equations (higher degree)

**Rational root theorem:** If p/q is a rational root of aₙxⁿ + ... + a₀, then p|a₀ and q|aₙ.

**Remainder theorem:** When f(x) divided by (x–a), remainder = f(a).

**Factor theorem:** (x–a) is a factor of f(x) if and only if f(a) = 0.

### Common Results
- For cubic ax³+bx²+cx+d=0, roots α,β,γ:
  - α+β+γ = –b/a
  - αβ+βγ+γα = c/a
  - αβγ = –d/a

---

## Inequalities (Quadratic)

For ax² + bx + c < 0 (a > 0):
- D < 0: no real roots → inequality never satisfied
- D = 0: satisfied nowhere (only = 0 at root)
- D > 0: satisfied between the roots α < x < β

For ax² + bx + c > 0 (a > 0): satisfied for x < α or x > β (outside roots)

---

## Practice Questions
1. Find modulus and argument of z = 1 + i√3.
2. If α, β are roots of x²–5x+6=0, find α²+β².
3. For what real k does x²+kx+1=0 have complex roots?
4. Express (1+i)/(1–i) in a+bi form.

> [!question]- Answers
> 1. |z| = √(1+3) = 2; arg = tan⁻¹(√3/1) = π/3 (60°); z = 2e^(iπ/3)
> 2. α+β=5, αβ=6; α²+β² = (α+β)²–2αβ = 25–12 = 13
> 3. D < 0: k²–4 < 0 → –2 < k < 2
> 4. Multiply by (1+i)/(1+i): (1+i)²/((1)²+(1)²) = (1+2i–1)/2 = 2i/2 = i → 0+1i

---
**Previous: [[M6 Vectors & 3D]]**
