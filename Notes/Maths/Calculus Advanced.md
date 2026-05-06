# Calculus Advanced — Depth for COMEDK

> [!tip] One Line
> COMEDK loves: tricky substitutions, definite integral properties, area between curves, differential equations, and curve analysis.

---

## Differentiation — Advanced

### Logarithmic Differentiation
Use when: product of many functions, or variable in both base and exponent.
```
y = f(x)^g(x) → ln y = g(x)·ln f(x) → differentiate both sides
```
Example: y = xˢⁱⁿˣ → ln y = sinx·ln x → y'/y = cosx·lnx + sinx/x → y' = xˢⁱⁿˣ(cosx·lnx + sinx/x)

### Higher Order Derivatives
Leibniz formula for nth derivative of product:
```
Dⁿ(uv) = Σ ⁿCₖ (Dᵏu)(Dⁿ⁻ᵏv)
```

### Tangent & Normal Applications
At point P(x₁,y₁):
- Length of tangent = y₁√(1 + 1/m²) where m = dy/dx at P
- Length of normal = y₁√(1 + m²)
- Subtangent = y₁/m
- Subnormal = y₁m

### Rate of Change Problems
Key setup: identify what rate is given (dV/dt, dr/dt, dh/dt etc.) and what is asked. Use chain rule.

Example: Spherical balloon inflated at 100 cm³/s, find rate of radius increase when r = 5cm.
dV/dt = 4πr²·dr/dt → 100 = 4π(25)·dr/dt → dr/dt = 100/100π = 1/π cm/s

---

## Integration — Advanced Techniques

### Integration by Partial Fractions — Full Types
**Type 1:** 1/(x–a)(x–b) = A/(x–a) + B/(x–b)

**Type 2:** 1/(x–a)² = A/(x–a) + B/(x–a)²

**Type 3:** (px+q)/(ax²+bx+c) → split as d/dx(ax²+bx+c) + constant, then integrate

**Type 4:** Rational with irreducible quadratic: 1/(x²+a²) → tan⁻¹; x/(x²+a²) → ½ln(x²+a²)

### Special Integrals (must memorize)
```
∫√(a²–x²) dx = x/2·√(a²–x²) + a²/2·sin⁻¹(x/a) + C
∫√(x²+a²) dx = x/2·√(x²+a²) + a²/2·ln|x+√(x²+a²)| + C
∫√(x²–a²) dx = x/2·√(x²–a²) – a²/2·ln|x+√(x²–a²)| + C
∫eˣ[f(x)+f'(x)] dx = eˣf(x) + C
```

### Definite Integral — Key Properties
```
∫₀^(π/2) sin^n x dx = ∫₀^(π/2) cos^n x dx = Wₙ   (Wallis formula)
W_n = [(n–1)/n]·[(n–3)/(n–2)]·...× π/2 (if n even) or ×1 (if n odd)
```

**King's property:** ∫₀^a f(x)dx = ∫₀^a f(a–x)dx
**Use to simplify:** ∫₀^(π/2) sinx/(sinx+cosx) dx = ∫₀^(π/2) cosx/(sinx+cosx) dx = π/4

**Periodicity:** If f has period T: ∫₀^(nT) f(x)dx = n·∫₀^T f(x)dx

### Reduction Formula
∫sinⁿx dx = –sinⁿ⁻¹x·cosx/n + (n–1)/n·∫sinⁿ⁻²x dx

---

## Differential Equations

### Types & Methods

**Separable:** dy/dx = f(x)g(y) → ∫dy/g(y) = ∫f(x)dx

**Homogeneous:** dy/dx = f(y/x) → put y = vx → dy/dx = v + x·dv/dx → separable

**Linear first-order:** dy/dx + P(x)y = Q(x)
→ Integrating factor: μ = e^∫P dx
→ Solution: y·μ = ∫Q·μ dx + C

**Bernoulli:** dy/dx + P(x)y = Q(x)yⁿ → divide by yⁿ, put z = y^(1–n) → linear

**Exact:** M dx + N dy = 0 where ∂M/∂y = ∂N/∂x
→ Solution: ∫M dx (treating y as const) + ∫(terms in N with no x) dy = C

---

## Area Under Curves — COMEDK Patterns

### Area between two parabolas
Example: y² = 4x and x² = 4y
Intersection: x⁴/16 = 4x → x(x³–64) = 0 → x = 0, 4
Area = ∫₀⁴ [√(4x) – x²/4] dx = [4x^(3/2)/3 – x³/12]₀⁴ = 32/3 – 64/12 = 32/3 – 16/3 = 16/3

### Area with x-axis
When curve crosses x-axis, split integral and take absolute values.

### Volume of Revolution
**Around x-axis:** V = π∫y² dx
**Around y-axis:** V = π∫x² dy

---

## Curve Sketching (Systematic)
1. Find domain
2. Symmetry (even/odd/periodic)
3. x and y intercepts
4. Vertical asymptotes (denominator = 0)
5. Horizontal/oblique asymptotes (x → ±∞)
6. f'(x) = 0 → critical points, increasing/decreasing intervals
7. f''(x) → concavity, inflection points
8. Sketch

---

## Practice (COMEDK style)

1. ∫₀^(π/2) sin²x·cos²x dx using reduction or property
2. Solve: dy/dx + 2y/x = x² (linear ODE)
3. Area enclosed by y=x² and y=x+2
4. If y = xˣ, find dy/dx at x=1

> [!question]- Answers
> 1. sin²x·cos²x = ¼sin²(2x) = ⅛(1–cos4x); ∫₀^(π/2) ⅛(1–cos4x)dx = ⅛[x–sin4x/4]₀^(π/2) = ⅛[π/2 – 0] = π/16
> 2. P=2/x, μ=e^∫2/x dx = x²; y·x² = ∫x²·x² dx = x⁵/5 + C; y = x³/5 + C/x²
> 3. x²=x+2 → x²–x–2=0 → x=–1,2; Area = ∫₋₁²(x+2–x²)dx = [x²/2+2x–x³/3]₋₁² = (2+4–8/3)–(½–2+1/3) = 10/3+7/6 = 27/6 = 9/2
> 4. y = xˣ → ln y = x ln x → y'/y = lnx + 1 → y' = xˣ(lnx+1); at x=1: y' = 1×(0+1) = 1
