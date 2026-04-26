# M4 Probability & Statistics

> [!tip] One Line
> P(A) = favorable/total. Conditional: P(A|B) = P(A∩B)/P(B). Bayes: reverse conditional. Binomial for repeated trials.

---

## Basic Probability

```
P(A) = n(A)/n(S)    (0 ≤ P(A) ≤ 1)
P(A') = 1 – P(A)
P(A ∪ B) = P(A) + P(B) – P(A ∩ B)
P(A ∪ B) = P(A) + P(B)    if A and B are mutually exclusive
```

**Equally likely outcomes:** P(each) = 1/n(S)

---

## Conditional Probability

```
P(A|B) = P(A ∩ B)/P(B)    (probability of A given B has occurred)
```

### Multiplication Rule
```
P(A ∩ B) = P(A) × P(B|A) = P(B) × P(A|B)
```

### Independent Events
A and B independent if P(A ∩ B) = P(A) × P(B)
→ Also: P(A|B) = P(A), P(B|A) = P(B)

---

## Total Probability & Bayes' Theorem

### Total Probability
If B₁, B₂, ..., Bₙ partition sample space:
```
P(A) = Σ P(A|Bᵢ) × P(Bᵢ)
```

### Bayes' Theorem
```
P(Bᵢ|A) = P(A|Bᵢ) × P(Bᵢ) / Σ P(A|Bⱼ) × P(Bⱼ)
```
Used to "reverse" conditional probability — prior → posterior.

---

## Random Variables & Distributions

### Expectation & Variance
```
E(X) = Σ xᵢP(xᵢ)    (mean/expected value)
Var(X) = E(X²) – [E(X)]²
SD = √Var(X)
```

### Bernoulli Trial
- Two outcomes: success (p) or failure (q = 1–p)
- Each trial independent

### Binomial Distribution
X ~ B(n, p): n Bernoulli trials.
```
P(X = r) = ⁿCᵣ × pʳ × qⁿ⁻ʳ    (r = 0, 1, 2, ..., n)
Mean = np
Variance = npq
SD = √(npq)
```

---

## Statistics

### Measures of Central Tendency
```
Mean (x̄) = Σxᵢ/n    (or Σfᵢxᵢ/Σfᵢ for grouped data)
Median: middle value (arrange in order)
Mode: most frequent value
```

For symmetric distribution: Mean = Median = Mode

### Measures of Dispersion
```
Range = max – min
Mean Deviation = Σ|xᵢ – x̄|/n
Variance (σ²) = Σ(xᵢ – x̄)²/n = Σxᵢ²/n – x̄²
SD (σ) = √Variance
Coefficient of Variation = (σ/x̄) × 100%
```

---

## Combinations & Permutations (quick)

```
nPr = n!/(n–r)!    (ordered arrangements)
nCr = n!/[r!(n–r)!]    (unordered selections)
nC0 = nCn = 1
nCr = nC(n–r)
```

**Useful identities:**
- (1+x)ⁿ = Σ ⁿCᵣ xʳ (Binomial theorem)
- Sum of all nCr = 2ⁿ

---

## Practice Questions
1. A bag has 3 red, 4 blue balls. Two drawn without replacement. P(both red)?
2. P(A) = 0.4, P(B) = 0.3, P(A∩B) = 0.1. Find P(A∪B) and P(A|B).
3. A coin tossed 6 times. P(exactly 4 heads)?
4. 10 numbers: 2,3,4,5,6,7,8,9,10,11. Find mean and variance.

> [!question]- Answers
> 1. P = (3/7) × (2/6) = 6/42 = 1/7
> 2. P(A∪B) = 0.4+0.3–0.1 = 0.6; P(A|B) = P(A∩B)/P(B) = 0.1/0.3 = 1/3
> 3. P(X=4) = ⁶C₄ × (1/2)⁴ × (1/2)² = 15/64
> 4. Mean = (2+3+...+11)/10 = 65/10 = 6.5; E(X²) = (4+9+16+...+121)/10 = 505/10 = 50.5; Var = 50.5 – 6.5² = 50.5 – 42.25 = 8.25

---
**Previous: [[M3 Matrices & Determinants]]**
**Next: [[M5 Coordinate Geometry]]**
