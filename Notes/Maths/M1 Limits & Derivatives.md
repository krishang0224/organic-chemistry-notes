# M1 Limits & Derivatives

> [!tip] One Line
> Limit = value a function approaches. Derivative = instantaneous rate of change = slope of tangent. Chain rule for compositions.

---

## Limits

### Standard Limits
```
lim(x→0) sinx/x = 1
lim(x→0) tanx/x = 1
lim(x→0) (1–cosx)/x² = 1/2
lim(x→0) (aˣ–1)/x = ln a
lim(x→0) (eˣ–1)/x = 1
lim(x→0) ln(1+x)/x = 1
lim(x→∞) (1+1/x)ˣ = e
lim(x→a) (xⁿ–aⁿ)/(x–a) = naⁿ⁻¹
```

### L'Hôpital's Rule
If limit gives 0/0 or ∞/∞ form:
```
lim f(x)/g(x) = lim f'(x)/g'(x)
```

### Sandwich Theorem
If g(x) ≤ f(x) ≤ h(x) and lim g = lim h = L, then lim f = L.

### Continuity
f(x) continuous at x = a if:
1. f(a) is defined
2. lim(x→a) f(x) exists
3. lim(x→a) f(x) = f(a)

---

## Differentiation

### Basic Rules
```
d/dx(xⁿ) = nxⁿ⁻¹
d/dx(eˣ) = eˣ
d/dx(aˣ) = aˣ ln a
d/dx(ln x) = 1/x
d/dx(log_a x) = 1/(x ln a)
d/dx(sin x) = cos x
d/dx(cos x) = –sin x
d/dx(tan x) = sec²x
d/dx(cot x) = –cosec²x
d/dx(sec x) = sec x tan x
d/dx(cosec x) = –cosec x cot x
```

### Inverse Trig
```
d/dx(sin⁻¹x) = 1/√(1–x²)
d/dx(cos⁻¹x) = –1/√(1–x²)
d/dx(tan⁻¹x) = 1/(1+x²)
d/dx(cot⁻¹x) = –1/(1+x²)
d/dx(sec⁻¹x) = 1/(x√(x²–1))
```

### Rules
```
Product rule: d/dx(uv) = u'v + uv'
Quotient rule: d/dx(u/v) = (u'v – uv')/v²
Chain rule: d/dx[f(g(x))] = f'(g(x)) · g'(x)
```

### Implicit Differentiation
Differentiate both sides w.r.t. x; treat y as function of x.
Example: x² + y² = r² → 2x + 2y(dy/dx) = 0 → dy/dx = –x/y

### Parametric Differentiation
If x = f(t), y = g(t): dy/dx = (dy/dt)/(dx/dt)

---

## Applications of Derivatives

### Tangent & Normal
- Slope of tangent at (x₁,y₁): m = f'(x₁)
- Tangent: y – y₁ = m(x – x₁)
- Normal: y – y₁ = (–1/m)(x – x₁)

### Maxima & Minima
**First derivative test:**
- f'(x) changes + to –: local max
- f'(x) changes – to +: local min

**Second derivative test:**
- f''(x) < 0: local max
- f''(x) > 0: local min
- f''(x) = 0: inflection point (check further)

### Increasing/Decreasing
- f'(x) > 0 on interval: f increasing
- f'(x) < 0 on interval: f decreasing

### Rolle's Theorem
If f continuous on [a,b], differentiable on (a,b), and f(a) = f(b), then ∃c ∈ (a,b) such that f'(c) = 0.

### Mean Value Theorem (MVT)
```
f'(c) = [f(b) – f(a)]/(b – a)    for some c ∈ (a,b)
```

---

## Practice Questions
1. lim(x→0) (sin 3x)/(sin 5x) = ?
2. Differentiate: y = x³ sin x
3. Find dy/dx if y = sin⁻¹(2x√(1–x²))
4. For f(x) = x³ – 3x + 2, find local max and min.

> [!question]- Answers
> 1. lim(sin3x/3x) × (5x/sin5x) × (3/5) = 1 × 1 × 3/5 = 3/5
> 2. dy/dx = 3x² sin x + x³ cos x (product rule)
> 3. Let x = sinθ; then y = sin⁻¹(2sinθ cosθ) = sin⁻¹(sin2θ) = 2θ = 2sin⁻¹x; dy/dx = 2/√(1–x²)
> 4. f'(x) = 3x²–3 = 0 → x = ±1; f''(1) = 6 > 0 → min at x=1, f(1)=0; f''(–1) = –6 < 0 → max at x=–1, f(–1)=4

---
**Next: [[M2 Integration]]**
