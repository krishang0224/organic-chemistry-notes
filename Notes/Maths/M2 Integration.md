# M2 Integration

> [!tip] One Line
> Integration = antiderivative = area under curve. Definite integral bounded. Key techniques: substitution, parts, partial fractions.

---

## Standard Integrals

```
∫xⁿ dx = xⁿ⁺¹/(n+1) + C    (n ≠ –1)
∫1/x dx = ln|x| + C
∫eˣ dx = eˣ + C
∫aˣ dx = aˣ/ln a + C
∫sin x dx = –cos x + C
∫cos x dx = sin x + C
∫tan x dx = ln|sec x| + C
∫cot x dx = ln|sin x| + C
∫sec x dx = ln|sec x + tan x| + C
∫cosec x dx = ln|cosec x – cot x| + C
∫sec²x dx = tan x + C
∫cosec²x dx = –cot x + C
∫sec x tan x dx = sec x + C
∫1/√(a²–x²) dx = sin⁻¹(x/a) + C
∫1/(a²+x²) dx = (1/a)tan⁻¹(x/a) + C
∫1/√(x²–a²) dx = ln|x + √(x²–a²)| + C
∫√(a²–x²) dx = (x/2)√(a²–x²) + (a²/2)sin⁻¹(x/a) + C
```

---

## Integration Techniques

### 1. Substitution
Replace variable: let u = g(x) → du = g'(x)dx
```
∫f(g(x))g'(x)dx → ∫f(u)du
```
Example: ∫2x(x²+1)⁵ dx → u = x²+1, du = 2x dx → ∫u⁵ du = u⁶/6 = (x²+1)⁶/6

### 2. Integration by Parts
```
∫u dv = uv – ∫v du
```
**ILATE** rule for choosing u (higher priority first):
- **I**nverse trig, **L**ogarithmic, **A**lgebraic, **T**rigonometric, **E**xponential

Example: ∫x eˣ dx → u = x, dv = eˣ dx → xeˣ – eˣ + C

### 3. Partial Fractions
For rational functions P(x)/Q(x) where deg(P) < deg(Q):

**Distinct linear factors:** 1/[(x–a)(x–b)] = A/(x–a) + B/(x–b)
**Repeated factors:** 1/(x–a)² = A/(x–a) + B/(x–a)²
**Irreducible quadratic:** 1/[(x–a)(x²+bx+c)] = A/(x–a) + (Bx+C)/(x²+bx+c)

### 4. Special Forms
```
∫(f'(x)/f(x)) dx = ln|f(x)| + C
∫[f(x) + f'(x)]eˣ dx = f(x)eˣ + C
```

---

## Definite Integrals

```
∫[a,b] f(x)dx = F(b) – F(a)    (Newton-Leibniz)
```

### Properties
```
∫[a,b] f(x)dx = –∫[b,a] f(x)dx
∫[a,b] f(x)dx = ∫[a,c] f(x)dx + ∫[c,b] f(x)dx
∫[a,b] f(x)dx = ∫[a,b] f(a+b–x)dx
∫[0,a] f(x)dx = ∫[0,a] f(a–x)dx
∫[–a,a] f(x)dx = 2∫[0,a] f(x)dx if f(x) is even; = 0 if f(x) is odd
∫[0,2a] f(x)dx = 2∫[0,a] f(x)dx if f(2a–x) = f(x); = 0 if f(2a–x) = –f(x)
```

### Fundamental Theorem
```
d/dx[∫[a,x] f(t)dt] = f(x)
```

---

## Area Under Curve

```
Area = ∫[a,b] |f(x)| dx    (take absolute value for areas below x-axis)
Area between two curves = ∫[a,b] [f(x) – g(x)] dx    (f above g)
```

---

## Practice Questions
1. ∫(2x + 3)⁵ dx
2. ∫x ln x dx
3. ∫₀^(π/2) sin x dx
4. Area bounded by y = x², x-axis, x = 0, x = 2

> [!question]- Answers
> 1. Let u = 2x+3, du = 2dx → (1/2)∫u⁵ du = u⁶/12 = (2x+3)⁶/12 + C
> 2. u = ln x, dv = x dx → (x²/2)ln x – ∫(x²/2)(1/x)dx = (x²/2)ln x – x²/4 + C
> 3. [–cos x]₀^(π/2) = –cos(π/2) + cos(0) = 0 + 1 = 1
> 4. ∫₀² x² dx = [x³/3]₀² = 8/3 sq. units

---
**Previous: [[M1 Limits & Derivatives]]**
**Next: [[M3 Matrices & Determinants]]**
