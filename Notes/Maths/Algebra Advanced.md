# Algebra Advanced — Sequences, Binomial, P&C

> [!tip] One Line
> COMEDK algebra: binomial term finding, AP/GP sum traps, P&C with restrictions, and complex number geometry.

---

## Sequences & Series

### AP (Arithmetic Progression)
```
aₙ = a + (n–1)d
Sₙ = n/2[2a + (n–1)d] = n/2[first + last]
```
**Arithmetic Mean:** AM = (a+b)/2; n AMs between a and b: d = (b–a)/(n+1)

### GP (Geometric Progression)
```
aₙ = arⁿ⁻¹
Sₙ = a(rⁿ–1)/(r–1)   for r ≠ 1
S∞ = a/(1–r)   for |r| < 1
```
**Geometric Mean:** GM = √(ab); GM² = AM × HM (AM–GM–HM inequality)

### Harmonic Progression
1/a, 1/(a+d), 1/(a+2d) — nth term: HM = 1/(1/a + (n–1)·d_arithmetic)
**HM of a and b:** H = 2ab/(a+b)

### Important Relations
- AM ≥ GM ≥ HM (for positive numbers, equality when all equal)
- AM × HM = GM²
- Sum of first n natural numbers: n(n+1)/2
- Sum of squares: n(n+1)(2n+1)/6
- Sum of cubes: [n(n+1)/2]²

### Arithmetic-Geometric Series (AGP)
a + (a+d)r + (a+2d)r² + ...
Multiply by r, subtract → use standard technique.

---

## Binomial Theorem

### General Term
(a+b)ⁿ: T_{r+1} = ⁿCᵣ × aⁿ⁻ʳ × bʳ

### Finding Specific Terms
- "Term independent of x" → set power of x = 0 → solve for r
- "Coefficient of xᵏ" → set power of x = k → solve for r → find ⁿCᵣ × coeff

### Middle Term
- n even: one middle term T_{n/2+1}
- n odd: two middle terms T_{(n+1)/2} and T_{(n+3)/2}

### Binomial Coefficients
```
ⁿC₀ + ⁿC₁ + ... + ⁿCₙ = 2ⁿ
ⁿC₀ – ⁿC₁ + ⁿC₂ – ... = 0
ⁿC₀² + ⁿC₁² + ... + ⁿCₙ² = ²ⁿCₙ
ⁿC₀·ⁿCᵣ + ⁿC₁·ⁿCᵣ₊₁ + ... = ²ⁿCₙ₋ᵣ (Vandermonde)
```

### Greatest Term
Find r where T_{r+1}/T_r ≥ 1 → largest r satisfying this is the greatest term.

---

## Permutations & Combinations

### Core Formulas
```
nPr = n!/(n–r)!
nCr = n!/[r!(n–r)!]
```

### With Restrictions

**Always together:** Treat as one unit → (n–k+1)! × k! (k = objects stuck together)

**Never together:** Total – (all together)

**Circular arrangement:** (n–1)! for n distinct objects; with clockwise = anticlockwise: (n–1)!/2

**Identical objects:** n objects where p, q, r identical: n!/(p!q!r!)

**Distribution into groups:**
- n distinct into groups of r, s, t (r+s+t=n, all distinct groups): n!/(r!s!t!)
- n identical into r distinct groups: ⁿ⁺ʳ⁻¹Cᵣ₋₁

### Derangements
Number of permutations where no element appears in original position:
```
D(n) = n! × Σ(–1)ᵏ/k!  for k=0 to n  ≈ n!/e
D(n) = n!·[1 – 1/1! + 1/2! – 1/3! + ... + (–1)ⁿ/n!]
```

---

## Complex Numbers — Advanced

### De Moivre's Theorem Applications
**nth roots of unity:** 1^(1/n) = e^(2πik/n), k = 0,1,...,n–1
They form a regular n-gon on the unit circle.

**Sum of roots:** 0 (always, for n ≥ 2)
**Product of roots:** (–1)^(n+1)
**Sum of pth powers:** n (if n|p) else 0

### Complex Number Geometry
- |z – z₀| = r: circle of radius r centered at z₀
- arg(z – z₁)/(z – z₂) = α: arc of circle
- Re(z) = k: vertical line; Im(z) = k: horizontal line
- |z – z₁| + |z – z₂| = 2a: ellipse with foci z₁, z₂

### Rotation
To rotate z by angle θ: multiply by e^(iθ) = cosθ + i sinθ

If A(z₁), B(z₂), C(z₃) and ∠BAC = θ:
```
(z₃–z₁)/(z₂–z₁) = |z₃–z₁|/|z₂–z₁| × e^(iθ)
```

### Logarithm of Complex Number
```
ln(re^(iθ)) = ln r + iθ
ln(–1) = iπ (since –1 = e^(iπ))
```

---

## Mathematical Induction (COMEDK sometimes asks)
1. Base case: verify for n=1 (or n=0)
2. Assume true for n=k
3. Prove for n=k+1 using the assumption

---

## Practice (COMEDK style)

1. Find term independent of x in (x + 1/x)¹²
2. In how many ways can 5 men and 5 women sit alternately in a row?
3. GP: first term 2, sum to infinity 8. Find common ratio.
4. Find all values of z if |z| = 1 and z + 1/z is real.

> [!question]- Answers
> 1. T_{r+1} = ¹²Cᵣ × x^(12–r) × x^(–r) = ¹²Cᵣ × x^(12–2r); independent: 12–2r=0 → r=6; T₇ = ¹²C₆ = 924
> 2. 5 men in a row: 5! ways; 5 women fill 5 gaps: 5! ways; but it's a row not circle: total = 5! × 5! × 2 (MWMWMW... or WMWMWM...) = 2 × 120 × 120 = 28800
> 3. S∞ = a/(1–r) → 8 = 2/(1–r) → 1–r = 1/4 → r = 3/4
> 4. z = e^(iθ), z+1/z = e^(iθ) + e^(–iθ) = 2cosθ which is always real! So ALL z on unit circle satisfy this.
