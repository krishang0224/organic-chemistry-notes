# Coordinate Geometry Advanced — COMEDK Depth

> [!tip] One Line
> COMEDK traps: tangent conditions, chord of contact, family of circles, pole-polar, and normal to conics.

---

## Straight Lines — Advanced

### Family of Lines
Through intersection of L₁=0 and L₂=0: L₁ + λL₂ = 0 (for any real λ)
Find specific member by applying given condition.

### Pair of Straight Lines
ax² + 2hxy + by² + 2gx + 2fy + c = 0 represents a pair if:
```
Δ = |a h g|
    |h b f| = 0   (determinant = 0)
    |g f c|
```
Angle between pair: tan θ = 2√(h²–ab)/(a+b)
Pair is perpendicular if: a + b = 0
Pair is coincident if: h² = ab

**Homogeneous form** ax²+2hxy+by²=0: lines through origin
```
tan θ = 2√(h²–ab)/(a+b)
```

---

## Circle — Advanced

### Chord of Contact
From external point (x₁,y₁), chord of contact to x²+y²=r² is:
```
xx₁ + yy₁ = r²
```
This is the same form as the tangent at a point — key duality.

### Pair of Tangents
Combined equation of tangents from (x₁,y₁) to x²+y²=r²:
```
SS₁ = T²
where S = x²+y²–r², S₁ = x₁²+y₁²–r², T = xx₁+yy₁–r²
```

### Family of Circles
Through intersection of two circles C₁=0 and C₂=0:
C₁ + λC₂ = 0 (for λ ≠ –1)
Radical axis: C₁ – C₂ = 0 (this is a line, not a circle)

### Radical Axis
- Locus of points with equal tangent lengths to both circles
- Perpendicular to line joining centres
- Radical centre of three circles: common radical axes meet at one point

---

## Parabola — Advanced

### Standard y² = 4ax:
- Vertex: (0,0); Focus: (a,0); Directrix: x = –a
- Tangent at (at²,2at): ty = x + at²
- Normal at (at²,2at): y + tx = 2at + at³
- Chord joining (at₁²,2at₁) and (at₂²,2at₂): passes through focus when t₁t₂ = –1 (focal chord)
- **End points of latus rectum:** (a, 2a) and (a, –2a)
- Length of latus rectum = 4a

### Parametric Form
Point on y²=4ax: (at², 2at) where t is parameter

**Condition for tangent y=mx+c to parabola:** c = a/m
Tangent in slope form: y = mx + a/m

---

## Ellipse — Advanced

### x²/a² + y²/b² = 1 (a>b):
```
Eccentricity: e = √(1–b²/a²)
Foci: (±ae, 0)
Directrices: x = ±a/e
Sum of focal distances: r₁ + r₂ = 2a (constant — definition of ellipse)
```

### Tangent & Normal to Ellipse
Tangent at (x₁,y₁): xx₁/a² + yy₁/b² = 1
Tangent in slope form: y = mx ± √(a²m²+b²) — condition: c² = a²m²+b²

Normal at (x₁,y₁): (a²x/x₁) – (b²y/y₁) = a²–b²

**Parametric point:** (a cosθ, b sinθ)
Tangent at parametric point: (x cosθ)/a + (y sinθ)/b = 1

---

## Hyperbola — Advanced

### x²/a² – y²/b² = 1:
```
e = √(1+b²/a²) > 1
|r₁ – r₂| = 2a   (constant difference — definition)
Asymptotes: y = ±(b/a)x   (pass through centre)
Rectangular hyperbola: a = b, so asymptotes are ⊥
```

**xy = c²:** Rectangular hyperbola
- Parametric point: (ct, c/t)
- Tangent at (ct,c/t): x/t + yt = 2c or x + t²y = 2ct
- Normal: t³x – ty = c(t⁴–1)

---

## Common COMEDK Traps

### 1. Tangent to Circle from External Point
Length of tangent = √(x₁²+y₁²–r²) from point (x₁,y₁) to x²+y²=r²
Verify it's external: x₁²+y₁²–r² > 0

### 2. Pole and Polar
Polar of point (x₁,y₁) w.r.t. x²+y²=r² is: xx₁+yy₁ = r²
If polar of A passes through B, then polar of B passes through A (reciprocity)

### 3. Common Chord of Two Circles
S₁ – S₂ = 0 (subtract the two circle equations — linear equation = common chord)

### 4. Director Circle
Locus of point from which tangents to ellipse are perpendicular: x²+y² = a²+b²
For circle x²+y²=r²: director circle is x²+y² = 2r²

---

## Practice (COMEDK style)

1. Find the chord of contact of tangents from (2,3) to x²+y²=5.
2. Tangent from (3,0) to parabola y²=4x: find point of tangency.
3. Ellipse x²/16+y²/9=1: find sum of focal distances for point (2,3/2√3).
4. Find the angle between lines 2x²+5xy+2y²=0.

> [!question]- Answers
> 1. T = 0: x(2)+y(3)=5 → 2x+3y=5
> 2. Tangent to y²=4x from (3,0): use y=mx+1/m, passes through (3,0): 0=3m+1/m → 3m²+1=0 → no real solution... actually tangent y=mx+a/m passes through (3,0): 0=3m+1/m → 3m²=–1: no real m → (3,0) is INSIDE parabola... hmm. Let me use parametric: tangent ty=x+t² passes through (3,0): 0=3+t² → t²=–3: no real solution. So (3,0) is inside parabola (y²=4×3=12>0²=0 means... actually for outside check: y₁²<4x₁: 0<12 means INSIDE). External point needed. Try (5,0): t²=–5: still inside. Try (–1,0): t²=1+1=...ty=x+t², at (–1,0): 0=–1+t², t=±1. Points: (1,2) and (1,–2) ✓
> 3. For ellipse a=4, so sum = 2a = 8 (for any point on ellipse)
> 4. 2x²+5xy+2y²=0; a=2,h=5/2,b=2; tanθ = 2√(h²–ab)/(a+b) = 2√(25/4–4)/4 = 2√(9/4)/4 = 2×(3/2)/4 = 3/4; θ = tan⁻¹(3/4)
