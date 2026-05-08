# Coordinate Geometry Advanced — Depth for COMEDK

> [!tip] One Line
> COMEDK traps: pair of tangents from external point, chord of contact, radical axis, pole-polar, parametric forms, and condition of tangency.

---

## Circle — Advanced

### Standard Forms
```
x² + y² = r²   (center origin)
(x–h)² + (y–k)² = r²   (center h,k)
x² + y² + 2gx + 2fy + c = 0   → center (–g,–f), r = √(g²+f²–c)
```

### Tangent to Circle
**At point (x₁,y₁) on circle x²+y²=r²:**
```
xx₁ + yy₁ = r²
```
**From external point:** use T² = S₁
```
T = xx₁ + yy₁ – r²   (chord of contact equation too)
```

**Length of tangent from external point (x₁,y₁):**
```
L = √(x₁² + y₁² – r²) = √S₁
```

### Chord of Contact
From point (x₁,y₁) to circle x²+y²=r²:
```
xx₁ + yy₁ = r²
```
(same form as tangent at point — but this is a chord joining two tangent points)

### Radical Axis
Two circles S₁=0, S₂=0: radical axis = S₁–S₂ = 0
Always perpendicular to line joining centers.
Three circles → radical center = intersection of radical axes.

### Family of Circles
Circles through intersection of S₁=0 and S₂=0: S₁ + λS₂ = 0

---

## Parabola — Advanced

### Standard: y² = 4ax
```
Focus: (a,0)   Directrix: x = –a
Vertex: (0,0)  Axis: x-axis
Parametric: (at², 2at)
```

**Tangent at parametric point (at², 2at):** ty = x + at²
**Normal:** y + tx = 2at + at³

**Chord of contact from (x₁,y₁):** yy₁ = 2a(x+x₁)

**Condition for tangent y = mx + c:** c = a/m

**Focal chord:** t₁t₂ = –1 (product of parameters = –1)

### Other Parabolas
```
x² = 4ay: opens up, focus (0,a), vertex origin
x² = –4ay: opens down
y² = –4ax: opens left
```

---

## Ellipse — Advanced

### Standard: x²/a² + y²/b² = 1, a > b
```
c² = a² – b²    e = c/a < 1
Foci: (±c, 0)   Directrices: x = ±a/e
Length of major axis = 2a, minor = 2b
Latus rectum length = 2b²/a
```

**Parametric:** (a cosθ, b sinθ)

**Tangent at (x₁,y₁):** xx₁/a² + yy₁/b² = 1

**Tangent in slope form:** y = mx ± √(a²m²+b²)

**Condition for tangency:** c² = a²m² + b²

**Auxiliary circle:** x² + y² = a²
Eccentric angle θ: P = (a cosθ, b sinθ) on ellipse; Q = (a cosθ, a sinθ) on auxiliary circle

### Sum property: SP + S'P = 2a (sum of focal distances constant)

---

## Hyperbola — Advanced

### Standard: x²/a² – y²/b² = 1
```
c² = a² + b²    e = c/a > 1
Foci: (±c, 0)
Asymptotes: y = ±(b/a)x
```

**Rectangular hyperbola:** a = b → xy = c² form
```
xy = c²: parametric (ct, c/t)
Tangent: x/t² + yt = 2c... or: x + t²y = 2ct
```

**SP – S'P = ±2a** (difference of focal distances constant)

---

## Straight Line — Advanced

### Angle Bisectors
For lines a₁x+b₁y+c₁=0 and a₂x+b₂y+c₂=0:
```
(a₁x+b₁y+c₁)/√(a₁²+b₁²) = ±(a₂x+b₂y+c₂)/√(a₂²+b₂²)
```
Acute bisector: choose sign using condition a₁a₂+b₁b₂ < 0 for "+"

### Family of Lines
Through intersection of L₁=0, L₂=0: L₁ + λL₂ = 0

### Pair of Lines
Homogeneous second-degree: ax²+2hxy+by²=0 represents pair through origin
```
m₁+m₂ = –2h/b    m₁m₂ = a/b
Angle between: tan θ = 2√(h²–ab)/(a+b)
Perpendicular: a+b = 0
Coincident: h² = ab
```

General second degree ax²+2hxy+by²+2gx+2fy+c=0 represents pair of lines when:
```
|a h g|
|h b f| = 0   (determinant condition)
|g f c|
```

---

## Distance Formulas (3D Review)
```
Distance between parallel planes ax+by+cz+d₁=0 and ax+by+cz+d₂=0:
|d₁–d₂|/√(a²+b²+c²)
```

---

## Practice (COMEDK style)

1. Find length of tangent from (5,4) to circle x²+y²–2x–4y+4=0
2. Common chord of x²+y²+2x+2y+1=0 and x²+y²+4x+3y+2=0
3. Tangent to y²=8x makes angle 45° with x-axis. Find point of tangency.
4. Find eccentricity of ellipse if length of latus rectum = half major axis.

> [!question]- Answers
> 1. S₁ = 25+16–10–16+4 = 19; L = √19
> 2. Radical axis: S₁–S₂=0 → (2x+2y+1)–(4x+3y+2)=0 → –2x–y–1=0 → 2x+y+1=0
> 3. c = a/m; y=mx+a/m for y²=4ax → here 4a=8,a=2; m=tan45°=1; y=x+2; sub into y²=8x: (x+2)²=8x → x²–4x+4=0 → x=2,y=4; point: (2,4)
> 4. LR = 2b²/a = ½(2a) = a → 2b²=a² → 2(a²–c²)=a² → a²=2c² → e=c/a=1/√2
