# Algebra Advanced — Depth for COMEDK

> [!tip] One Line
> COMEDK algebra traps: sum of series, complex roots, log inequalities, AM-GM-HM, binomial middle term, and permutation traps.

---

## Sequences & Series — Advanced

### AP/GP/HP Key Results
```
AP: Sₙ = n/2(2a + (n–1)d)    Tₙ = a + (n–1)d
GP: Sₙ = a(rⁿ – 1)/(r–1)    S∞ = a/(1–r)  |r| < 1
HP: 1/a, 1/(a+d), 1/(a+2d)...  Tₙ = 1/(a+(n–1)d)
```

**AM–GM–HM inequality:**
```
AM ≥ GM ≥ HM   (equality when all terms equal)
AM = (a+b)/2,  GM = √(ab),  HM = 2ab/(a+b)
AM × HM = GM²
```

### Sum of Special Series
```
Σk = n(n+1)/2
Σk² = n(n+1)(2n+1)/6
Σk³ = [n(n+1)/2]²
```

**Arithmetico-Geometric Series (AGP):**
1, 2x, 3x², 4x³... → S = 1/(1–x)² for |x| < 1

Method: S – xS = 1 + x + x² + ... = 1/(1–x) → S = 1/(1–x)²

---

## Binomial Theorem — Advanced

### General Term
```
T_(r+1) = ⁿCᵣ · aⁿ⁻ʳ · bʳ
```

**Middle term:**
- n even: T_(n/2 + 1) — one middle term
- n odd: T_((n+1)/2) and T_((n+3)/2) — two middle terms

**Greatest term:** Find r where T_(r+1)/Tᵣ ≥ 1, then T_(r+1)/T_(r+2) ≥ 1

### Properties of ⁿCᵣ
```
ⁿCᵣ + ⁿCᵣ₋₁ = ⁿ⁺¹Cᵣ
ⁿC₀ + ⁿC₁ + ... + ⁿCₙ = 2ⁿ
ⁿC₀ – ⁿC₁ + ⁿC₂ – ... = 0
```

### Binomial with Negative/Fractional Index
```
(1+x)ⁿ = 1 + nx + n(n–1)/2! x² + ...   |x| < 1
(1+x)⁻¹ = 1 – x + x² – x³ + ...
(1–x)⁻¹ = 1 + x + x² + x³ + ...
```

---

## Logarithms — Advanced

### Key Properties
```
log_a(mn) = log_a m + log_a n
log_a(m/n) = log_a m – log_a n
log_a(mⁿ) = n·log_a m
log_a b = log_c b / log_c a   (change of base)
log_a b = 1/log_b a
```

### Log Inequalities
If base > 1: log_a x > log_a y → x > y (same direction)
If 0 < base < 1: log_a x > log_a y → x < y (reverses)

**Domain of log:** argument must be > 0

### Natural Log Limits
```
lim(x→0) ln(1+x)/x = 1
lim(x→0) (eˣ – 1)/x = 1
lim(x→∞) (1 + 1/x)ˣ = e
```

---

## Permutations & Combinations — Traps

### Key Formulas
```
ⁿPᵣ = n!/(n–r)!
ⁿCᵣ = n!/[r!(n–r)!]
```

### Common Traps
1. **Identical objects:** arrange n things with p alike, q alike → n!/(p!q!)
2. **Circular permutation:** (n–1)! for n distinct objects in circle
3. **Necklace:** (n–1)!/2 (can flip)
4. **All together:** treat group as single unit
5. **None together:** gaps method

**Number of diagonals in n-gon:** ⁿC₂ – n = n(n–3)/2

**Derangements** (no element in original position):
D_n = n![1 – 1/1! + 1/2! – 1/3! + ... + (–1)ⁿ/n!]

---

## Quadratic Equations — Deep

### Nature of Roots — Full Table
| Discriminant | Roots |
|---|---|
| D > 0 | Real, unequal |
| D = 0 | Real, equal |
| D < 0 | Complex conjugates |
| D = perfect square | Rational |

### Vieta's Formulas
For ax² + bx + c = 0:
- α + β = –b/a
- αβ = c/a
- α – β = √D/a

**Sum of squares:** α² + β² = (α+β)² – 2αβ
**Sum of cubes:** α³ + β³ = (α+β)³ – 3αβ(α+β)

### Graphs and Signs
- a > 0: parabola opens up; both roots same sign → c/a > 0
- f(0) = c → sign of c tells root positions relative to origin
- f(k) > 0 means k lies outside both roots (a > 0 case)

---

## Mathematical Induction & Inequality Tricks

### Induction Steps
1. Verify P(1)
2. Assume P(k)
3. Prove P(k+1) using P(k)

### Inequality: Useful Results
```
n! > 2ⁿ⁻¹  for n ≥ 3
(1 + 1/n)ⁿ < e < (1 + 1/n)ⁿ⁺¹
For a,b > 0: (a+b)/2 ≥ √(ab)
```

---

## Practice (COMEDK style)

1. Find the coefficient of x⁵ in (2x – 1/x)⁷
2. If α, β are roots of 2x² – 5x + 3 = 0, find α³ + β³
3. Sum: 1 + 2x + 3x² + ... to ∞ for |x| < 1
4. How many 4-digit numbers with no digit repeated and first digit ≠ 0?

> [!question]- Answers
> 1. T_(r+1) = ⁷Cᵣ(2x)^(7–r)(–1/x)^r = ⁷Cᵣ·2^(7–r)·(–1)^r·x^(7–r–r); for x⁵: 7–2r=5 → r=1; T₂ = ⁷C₁·2⁶·(–1) = 7·64·(–1) = –448
> 2. α+β = 5/2, αβ = 3/2; α³+β³ = (α+β)³–3αβ(α+β) = 125/8 – 3·(3/2)·(5/2) = 125/8 – 45/4 = 125/8 – 90/8 = 35/8
> 3. S = 1/(1–x)²
> 4. First digit: 9 choices (1–9); remaining 3 from 9 remaining digits: 9×8×7 = 9×P(9,3)/9... directly: 9 × 9 × 8 × 7 = 4536
